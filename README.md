###### English

# Fullstack Boilerplate for MERN with Typescript

A simple boilerplate designed to get fullstack projects up and running quickly using MERN (MySQL, Express, React and Node.js) with Typescript, while providing a consistent developer experience, with tools like Volta, Husky, Lint-staged and ESLint. On the front-end, it uses Next.js 13 and Sass, and on the back-end, Sequelize.

### Features

- Consistent code standards: on every commit Husky executes Lint-staged, running linters, formating with Prettier and type checking all staged files.
- Linters: ESLint for .tsx and .ts files and Stylelint for .scss and .css files

- Standardized commit messages with Commitlint and Angular Conventional Commits

- Node version locking with Volta

- Docker: easily run the whole app with a single command

#### Front-end

- Sass: Syntactically Awesome Style Sheets aka CSS with superpowers

- SVGR: use .svg images as React components

- Next.js pages router

#### Back-end

- RESTful API with Node.js, Express, MySQL and Sequelize

### Requirements

- Node ^16

- npm ^8

- Docker if you want to use it to run the app

- Volta if you want to automatically manage Node and npm versions

### Getting started

#### With Docker:

To use this boilerplate:

```shell
git clone https://github.com/igordosreis/boilerplate-fullstack project-name
npm run setup
```

Or click the 'Use this template' button at the top of this repository and then clone the newly created repository. After cloning, run:

```shell
npm run setup
```

If you want to use Volta:

```shell
curl https://get.volta.sh | bash
```

To run the project in development mode, on the root of the project run:

```shell
docker compose up -d
```

#### Locally:

To use this boilerplate:

```shell
git clone https://github.com/igordosreis/boilerplate-fullstack project-name
npm run setup:local
```

Or click the 'Use this template' button at the top of this repository and then clone the newly created repository. After cloning, run on the root folder:

```shell
npm run setup:local
```

If you want to use Volta:

```shell
curl https://get.volta.sh | bash
```

To run the project locally in development mode, do the following steps:

1. On the front-end folder of the project, open a new terminal window and run:

```shell
npm run dev
```

2. On the back-end folder of the project, open a new terminal window and run:

```shell
npm run dev
```

The server uses port `3071`. You can change this by using the provided .env file: remove the `.example` and change the value of the SERVER_PORT variable. Or change the port on the back-end/src/server.ts file.

3. Create a new MySQL 8 server.

The database uses port `3306`, username as `root` and password as `123456`.
You can change this by using the provided .env file: remove the `.example` and change the value of the DB_PORT, DB_USER, DB_PASS variables, respectively. Or change these values on the back-end/src/database/config/database.ts file.

---

###### Português

# Boilerplate Fullstack para MERN com Typescript

<!-- Um boilerplate simples concebido para rapidamente iniciar projetos usando Next.js, Typescript e Sass e também para prover uma experiência de desenvolvimento consistente, através de ferramentas como Volta, Husky, Lint-staged e ESLint.

### Funcionalidades

- Padrões de código consistentes: em cada commit o Husky executa o Lint-staged, rodando linters, formatando com Prettier e fazendo checagem de tipos em todos os arquivos staged.
- Linters: ESLint para arquivos .tsx e .ts and Stylelint para arquivos .scss e .css
- Mensagens de commit padronizadas com Commitlint e Angular Conventional Commits
- Versão do Node fixa com o Volta

- Sass: Syntactically Awesome Style Sheets também conhecido como CSS com super poderes

- SVGR: use imagens .svg como componentes de React

- Pages router do Next

### Requirements

- Node v16+

- npm v8+

- Volta para automaticamente gerenciar as versões do Node e do npm

### Como utilizar

Para usar esse boilerplate:

```shell
git clone https://github.com/igordosreis/boilerplate-fullstack nome-do-projeto
npm install
```

Ou clique no botão 'Use this template' no topo desse repositório e então clone o repositório criado. Após clonar, rode:
```shell
npm install
```

Caso você queira usar o Volta:

```shell
curl https://get.volta.sh | bash
```

Para rodar o projeto localmente em modo de desenvolvimento:

```shell
npm run dev
``` -->
