# Professional Web Project

Projeto criado para aplicar práticas profissionais de desenvolvimento web,
com foco em código limpo, arquitetura, Git e mentalidade sênior.

## Estrutura do Projeto

O projeto segue uma organização baseada em separação de responsabilidades,
facilitando manutenção, escalabilidade e colaboração em equipe.

.
├── public/
│ ├── assets/
│ │ ├── css/
│ │ │ └── style.css
│ │ ├── img/
│ │ └── js/
│ │ └── app.js
│ └── index.html
├── src/
│ ├── css/
│ │ ├── base/
│ │ ├── components/
│ │ └── utilities/
│ └── js/
│ ├── components/
│ └── utils/
├── tests/
└── README.md

### 📁 public/

Contém os arquivos que são **servidos diretamente ao navegador**.
Nenhuma lógica sensível ou código fonte de desenvolvimento deve ficar aqui.

- **index.html**: ponto de entrada da aplicação
- **assets/**: arquivos estáticos processados ou copiados para produção

### 📁 public/assets/

Arquivos estáticos utilizados pela aplicação em runtime.

- **css/**: arquivos CSS finais (gerados ou organizados)
- **js/**: bundle ou scripts finais usados pelo navegador
- **img/**: imagens, ícones e mídias

### 📁 src/

Código fonte real do projeto, organizado por responsabilidade.
Esse diretório **não é servido diretamente** ao usuário final.

### 📁 src/css/

Estilos organizados de forma modular:

- **base/**: reset, variáveis, tipografia, estilos globais
- **components/**: estilos específicos de componentes
- **utilities/**: classes utilitárias (helpers, espaçamentos, estados)

### 📁 src/js/

Código JavaScript organizado por domínio:

- **components/**: componentes da interface e lógica associada
- **utils/**: funções utilitárias reutilizáveis

### 📁 tests/

Testes automatizados (unitários, integração ou E2E),
garantindo confiabilidade e segurança nas mudanças do código.

### 📄 .gitignore

Define arquivos e diretórios que não devem ser versionados,
como dependências, builds e arquivos temporários.
