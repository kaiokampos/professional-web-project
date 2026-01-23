# Professional Web Project

Projeto criado para aplicar **práticas profissionais de desenvolvimento web**,  
com foco em:

- código limpo e legível
- arquitetura escalável
- organização semântica
- uso correto de Git (branches, commits e PRs)
- mentalidade de engenharia, não apenas visual

Este repositório serve como **portfólio técnico** e como **base reutilizável** para projetos reais.

---

## 🎯 Objetivo do Projeto

Demonstrar como um desenvolvedor profissional estrutura um projeto front-end desde o início, pensando em:

- manutenção a longo prazo
- colaboração em equipe
- clareza para revisores e recrutadores
- evolução incremental e control reminded (sem gambiarras)

---

## 🚀 Como rodar o projeto

Por enquanto, não há build pipeline.

1. Clone o repositório
2. Abra o arquivo abaixo no navegador:

```bash
public/index.html


📂 public/

Contém apenas arquivos servidos diretamente ao navegador.

Nada aqui deve conter lógica de desenvolvimento ou código experimental.

index.html
Entrada da aplicação (HTML semântico)

assets/
Arquivos finais usados em runtime (CSS, JS, imagens)

📂 src/

Código-fonte real do projeto, organizado para desenvolvimento e manutenção.
Esse diretório não é servido diretamente ao usuário.

📂 src/css/

Arquitetura CSS modular:

base/
Fundamentos globais (reset, variáveis, tipografia)

layout/
Estrutura da página (grid, sections, containers)

components/
Componentes reutilizáveis (buttons, cards, header, footer)

utilities/
Classes utilitárias e helpers

main.css
Entry point que importa todos os módulos de CSS🌿 Workflow de Git

O projeto segue um fluxo profissional de branches:

main     → código estável (produção)
develop  → integração contínua
feature/* → desenvolvimento de funcionalidades


📝 Padrão de Commits

Utilizamos Conventional Commits:

feat(scope): descrição

refactor(scope): descrição

fix(scope): descrição

chore(scope): descrição

📁 Estrutura do Projeto

O projeto segue separação clara de responsabilidades, evitando acoplamento
e facilitando evolução.

.
├── public/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css
│   │   ├── img/
│   │   └── js/
│   │       └── app.js
│   └── index.html
├── src/
│   └── css/
│       ├── base/
│       ├── components/
│       ├── layout/
│       ├── utilities/
│       └── main.css
└── README.md
```
