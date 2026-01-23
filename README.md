# Professional Web Project

Base profissional para criação de sites e portfólios, focada em **arquitetura limpa**, **HTML semântico**, **CSS modular** e **boas práticas reais de mercado**.

Este projeto não é um template genérico: ele foi pensado para servir como **fundação sólida** para produtos web que precisam ser claros, escaláveis e fáceis de manter.

---

## 🎯 Objetivo do projeto

Criar uma base de front-end que:

- Seja fácil de entender para outros desenvolvedores
- Escale sem virar um CSS/HTML desorganizado
- Utilize separação clara de responsabilidades
- Siga padrões usados em times profissionais

---

## 🧠 Conceitos aplicados

- HTML semântico e acessível
- CSS modular (por responsabilidade, não por página)
- Organização em camadas (base, layout, components, utilities)
- Design simples, legível e funcional
- Git Flow para controle de versões

---

## 📁 Estrutura do projeto

```
.
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── style.css      # CSS final compilado
│   │   └── js
│   │       └── app.js         # JS principal
│   └── index.html             # HTML final
├── src
│   └── css
│       ├── base               # Reset, variáveis e tipografia
│       ├── layout             # Grid e seções
│       ├── components         # Componentes reutilizáveis
│       ├── utilities          # Helpers utilitários
│       └── main.css           # Arquivo central de imports
├── README.md
└── .gitignore
```

---

## 🎨 Arquitetura CSS

### Base

Responsável pelos fundamentos do projeto:

- `reset.css`
- `variables.css`
- `typography.css`
- `globals.css`

### Layout

Define estruturas de página:

- Grid
- Espaçamentos globais
- Seções

### Components

Cada componente tem seu próprio arquivo:

- header
- hero
- about
- services
- projects
- contact
- buttons
- cards
- footer

Nada de CSS gigante ou genérico demais.

### Utilities

Classes pequenas e utilitárias para ajustes pontuais.

---

## 🧩 HTML

- Uso correto de `header`, `main`, `section`, `article`, `footer`
- Atributos `aria` quando necessário
- Estrutura clara e previsível

O HTML conversa diretamente com o CSS — sem gambiarras.

---

## 🌱 Fluxo de Git (Git Flow)

Branches principais:

- `main` → versão estável / produção
- `develop` → integração contínua
- `feature/*` ou `chore/*` → desenvolvimento

Exemplo de fluxo:

```bash
git checkout develop
git checkout -b feature/nova-secao
# trabalha
# commit
git push origin feature/nova-secao
```

Depois, merge para `develop`.

---

## 🚀 Como rodar o projeto

Projeto 100% estático.

Opções:

- Abrir o `public/index.html` direto no navegador
- Usar Live Server (VS Code)
- Servir com qualquer servidor estático simples

---

## 👤 Autor

**Kaio Campos**
Desenvolvedor Web focado em código limpo, arquitetura e soluções profissionais.

- GitHub: [https://github.com/kaiokampos](https://github.com/kaiokampos)
- Email: [kaiocamposti@gmail.com](mailto:kaiocamposti@gmail.com)

---

## 📌 Observação final

Este projeto foi construído com mentalidade de **produto real**, não de tutorial.

Se você entende essa base, você entende como projetos profissionais realmente funcionam.
