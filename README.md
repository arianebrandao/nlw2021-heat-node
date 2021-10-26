<h1 align="center">
  <img alt="dowhile2021" title="DO WHILE 2021" src=".github/logo.png" />
</h1>

<br>

<p align="center">
  <img alt="DO WHILE 2021" src=".github/app.png" width="100%">
</p>

## 🚀 NLW Heat - DO WHILE

Esse projeto foi desenvolvido durante a semana do evento [DO WHILE 2021](https://nextlevelweek.com) da RocketSeat.

## Projeto

O objetivo do evento é desenvolver uma aplicação completa, desde o back-end em Node.js, front-end para web em ReactJS,
front-end mobile em React Native e para finalizar, um microserviço com Elixir. Este projeto consiste em um sistema para enviar e
visualizar mensagens em tempo real sobre o evento, para enviar uma mensagem o usuário deve estar logado com sua conta no Github.

## Layout

Você pode visualizar o layout do projeto através [desse link](https://www.figma.com/community/file/1031699316177416916). É necessário ter conta no [Figma](http://figma.com/) para acessá-lo.

## Stage 1 – Aula prática

Nessa aula criamos o backend da aplicação utilizando NodeJS. Nesse projeto iremos utilizar Typescript, que auxilia no aumento da produtividade em desenvolvimento; vamos utilizar o Prisma ORM, para trabalhar com banco de dados e Socket.IO para trabalhar comunicação em tempo real.

## Front-end

Você pode consumir essa aplicação usando [esse front-end para web (em ReactJS)](https://github.com/arianebrandao/nlw2021-heat-web) ou [esse para mobile (em React Native)](https://github.com/arianebrandao/nlw2021-heat-reactnative).

## Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [NodeJS](https://nodejs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma ORM](https://www.prisma.io)
- [Socket.IO](https://socket.io)
- [Axios](https://axios-http.com)

## Como executar

- Clone o repositório
- Instale as dependências com `yarn`
- Importe as tabelas do SQLite com `yarn prisma migrate dev`
- Inicie o servidor com `yarn dev`

Agora você pode acessar [`localhost:4000`](http://localhost:4000) do seu navegador.

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.