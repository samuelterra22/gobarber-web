# Gobarber Web

![CI](https://github.com/samuelterra22/gobarber-web/workflows/CI/badge.svg)

<h1 align="center">
  <img alt="Gobarber" src="https://res.cloudinary.com/eliasgcf/image/upload/v1588625369/GoBarber/logo_iw1v9f.svg" width="200px">
</h1>

<p align="center">
  <a href="#page_with_curl-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#books-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-começando">Começando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como Contribuir</a>&nbsp;&nbsp;&nbsp;
</p>

<h1 align="center">
  <img alt="Mockup GoBarber" src="https://res.cloudinary.com/samuelterra22/image/upload/v1613479461/mockup_gobarber.png">
</h1>

## :page_with_curl: Sobre
Este repositório contém o projeto Web em React.js utilizando TypeScript referente à aplicação GoBarber desenvolvida no Bootcap GoStack da [Rocketseat](https://rocketseat.com.br/).

A aplicação Web se refere a uma plataforma de agendamento de serviços para proprietários de barbearias ou salões de beleza.
A aplicacao consome recursos de uma [API REST](https://github.com/samuelterra22/gobarber-api) disponibilizando recursos para o usuário ter acesso a todos os prostadores de serviços cadastrados.
Com isso, é possível escolher um determinado prestador para o agendamento na barbearia.

Já o prestador de serviço, consegue ter acesso a todos os seus horários, podendo ver todos os que estão ocupados quanto os que estão disponíveis.

## 🚀 Tecnologias

Tecnologias utilizadas no desenvolvimento da API:

- [TypeScript](https://www.typescriptlang.org/)
- [JWT-token](https://jwt.io/)
- [uuid v4](https://github.com/thenativeweb/uuidv4/)
- [Date-fns](https://date-fns.org/)
- [Jest](https://jestjs.io/)
- [SuperTest](https://github.com/visionmedia/supertest)
- [Husky](https://github.com/typicode/husky)
- [Commitlint](https://github.com/conventional-changelog/commitlint)
- [Commitizen](https://github.com/commitizen/cz-cli)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)


## :books: Requisitos
- Ter [**Git**](https://git-scm.com/) para clonar o projeto.
- Ter [**Node.js**](https://nodejs.org/en/) instalado.
- Ter [**Docker**](https://www.docker.com/) rodando um container PostgreSQL.

## :gear: Começando
``` bash
  # Clonar o projeto:
  $ git clone https://github.com/samuelterra22/gobarber-web

  # Entrar no diretório:
  $ cd gobarber-web

  # Instalar as dependências
  $ yarn

  # Fazer uma copia do arquivo '.env.example' para '.env'
  # e configurar suas variáveis de ambiente.
  $ cp .env.example .env

  # Para terminar, execute a aplicação
  $ yarn start
```

## 🤔 Como contribuir

**Faça um fork deste repositório**

```bash
# Fork usando a linha de comando oficial do GitHub
# Se você não tiver a CLI do GitHub, use o site para fazer isso.

$ gh repo fork samuelterra22/gobarber-web
```

**Siga os passos abaixo**

```bash
# Clone seu fork
$ git clone your-fork-url && cd gobarber-web

# Crie uma branch com sua feature
$ git checkout -b my-feature

# Faça o commit com suas mudanças
$ git commit -m 'feat: My new feature'

# Envie o código para sua branch remote
$ git push origin my-feature
```

Depois que seu pull request for aceito e a feature estiver na branch principal, você pode deletar sua branch

Feito com ❤️ por Samuel Terra 👋🏻 [Vamos de LinkedIn!](https://www.linkedin.com/in/samuelterra22/)
