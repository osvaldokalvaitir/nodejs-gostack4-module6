# Node - Módulo 6

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/osvaldokalvaitir/node-modulo6/blob/master/LICENSE)
![](https://img.shields.io/github/package-json/v/osvaldokalvaitir/node-modulo6.svg)
![](https://img.shields.io/github/last-commit/osvaldokalvaitir/node-modulo6.svg?color=red)
![](https://img.shields.io/github/languages/top/osvaldokalvaitir/node-modulo6.svg?color=yellow)
![](https://img.shields.io/github/languages/count/osvaldokalvaitir/node-modulo6.svg?color=lightgrey)
![](https://img.shields.io/github/languages/code-size/osvaldokalvaitir/node-modulo6.svg)
![](https://img.shields.io/github/repo-size/osvaldokalvaitir/node-modulo6.svg?color=blueviolet)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

Deploy e CI usando Heroku, GitHub e mLab. Ou usando Ubuntu, DigitalOcean, GitHub, MongoDB, PM2, Nginx e Buddy.

*Obs: Este repositório é uma cópia do [Node - Módulo 3](https://github.com/osvaldokalvaitir/node-modulo3) para realização de deploy e entrega contínua.*

## Índice

- [Desenvolvimento](#desenvolvimento)

  - [Configurações Iniciais](#configurações-iniciais)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Configuração das Variáveis de Ambiente](#configuração-das-variáveis-de-ambiente)

  - [Execução do Projeto](#execução-do-projeto)

- [Utilizados no Projeto](#utilizados-no-projeto)

  - [Bibliotecas](#bibliotecas)

  - [APIs](#apis)

  - [Ferramentas](#ferramentas)

## Desenvolvimento

### Configurações Iniciais

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga `Configurações Iniciais`.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Instalação de Projeto`.

### Configuração das Variáveis de Ambiente

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/dotenv.md) e siga `Configuração de Variáveis de Ambiente`.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Execução de Projeto`.

## Utilizados no Projeto

### Bibliotecas

- [@sentry/node](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@sentry-node.md)

- [bcrypt.js](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/bcryptjs.md)

- [dotenv](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/dotenv.md)

- [ESLint](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint.md)

- [Express](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express.md)

- [Express Async Handler](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express-async-handler.md)

- [Express Handlebars](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express-handlebars.md)

- [Express Handlebars plugin for Nodemailer](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/nodemailer-express-handlebars.md)

- [Express Validation](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express-validation.md)

- [Joi](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/joi.md)

- [Json Web Token](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/jsonwebtoken.md)

- [Kue](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/kue.md)

- [Mongoose](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/mongoose.md)

- [Mongoose Paginate](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/mongoose-paginate.md)

- [Nodemailer](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/nodemailer.md)

- [Nodemon](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/nodemon.md)

- [requireDir](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/requiredir.md)

- [Youch](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/youch.md)

###### Servidor Ubuntu

- [PM2](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/pm2.md) - Siga `Comandos` para configurar o servidor PM2.

### APIs

- **Interna**

  - **Rotas**

    - Intenções de Compras

      - Adiciona nova intenção de compra

    - Anúncios

        - Lista todos os anúncios
        - Lista somente dados de um anúncio
        - Adiciona novos anúncios
        - Edita dados de anúncios existentes
        - Exclui anúncios existentes

    - Sessões

        - Adiciona novas sessões

    - Usuários

        - Adiciona novos usuários

### Ferramentas

- [Docker](https://github.com/osvaldokalvaitir/projects-settings/blob/master/virtualization/docker/docker.md)

  - Imagem do Redis: [redis:alpine](https://github.com/osvaldokalvaitir/projects-settings/blob/master/virtualization/docker/images/redis-alpine.md)

- [Git](https://github.com/osvaldokalvaitir/projects-settings/blob/master/version-control/git.md)

- [GitHub](https://github.com/osvaldokalvaitir/projects-settings/blob/master/version-control/github.md)

- [Mailtrap](https://github.com/osvaldokalvaitir/projects-settings/blob/master/email/mailtrap.md)

- [Insomnia](https://github.com/osvaldokalvaitir/projects-settings/blob/master/api/insomnia.md)

- [Sentry](https://github.com/osvaldokalvaitir/projects-settings/blob/master/error/sentry.md)

###### Servidor Heroku

- [Heroku](https://github.com/osvaldokalvaitir/projects-settings/blob/master/paas/heroku.md) - Siga `Criar app > Projeto Node.js` para criar um app.

- [mLab](https://github.com/osvaldokalvaitir/projects-settings/blob/master/database/mongodb/mlab.md) - Siga `Criar banco de dados` para criar um banco de dados e `Criar usuário` para criar um usuário.

###### Servidor Ubuntu

- [Buddy](https://github.com/osvaldokalvaitir/projects-settings/blob/master/ci-cd/buddy.md) - Siga `Criar app` para criar um app.

- [DigitalOcean](https://github.com/osvaldokalvaitir/projects-settings/blob/master/server/digitalocean.md)

- [MongoDB](https://github.com/osvaldokalvaitir/projects-settings/blob/master/database/mongodb/mongodb.md) - Siga `Instalação > Ubuntu` para realizar a instalação.

- [Nginx](https://github.com/osvaldokalvaitir/projects-settings/blob/master/web-server/nginx.md) - Siga `Setar Arquivo de Configuração > Linux` para setar o arquivo de configuração.

- [Ubuntu](https://github.com/osvaldokalvaitir/projects-settings/blob/master/os/ubuntu.md) - Siga `Criar servidor` para criar um servidor.
