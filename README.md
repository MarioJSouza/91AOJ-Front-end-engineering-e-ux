<h1 align="center">
   <img src='.github/assets/logo.png' style="border-radius:50%" />
</h1>

<h1 align="center">
   FIAP Challenge
</h1>

<p align="center">
  <img alt="fiap" src="https://badgen.net/badge/hubla/Challenge/b">

  <a href="https://github.com/Zagetsus">
    <img alt="Made by fiap group" src="https://badgen.net/badge/made by/Grupo Fiap/b">
  </a>
</p>

<p align="center">
  <a href="#about">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#run-project">Como rodar o Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#participants">Participantes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## Sobre o projeto <a href='about'></a>


O projeto Vue.js Todo é uma aplicação web dinâmica e responsiva desenvolvida utilizando o framework Vue.js. Este projeto tem como objetivo principal oferecer uma experiência de gerenciamento de tarefas intuitiva e eficiente para os usuários. Com uma interface amigável e moderna, os usuários podem facilmente adicionar e marcar como concluídas suas tarefas diárias.

A aplicação Todo construída em Vue.js utiliza conceitos como componentização para garantir um código limpo e organizado, facilitando sua manutenção e escalabilidade. Além disso, integra recursos avançados como Vue Router para uma navegação fluida entre diferentes seções da aplicação, e Vuex para o gerenciamento centralizado do estado da aplicação, garantindo consistência e eficiência no fluxo de dados.

Com um design responsivo, o projeto Vue.js Todo oferece uma experiência perfeita em uma variedade de dispositivos, desde desktops até smartphones, permitindo que os usuários gerenciem suas tarefas em qualquer lugar e a qualquer momento. Sua arquitetura robusta e suas funcionalidades intuitivas fazem dele uma escolha ideal para aqueles que buscam uma solução eficaz para organização pessoal e profissional de suas atividades diárias.

### Requisitos:

- [NodeJS `>18.13.0`](https://nodejs.org/en/)
- [Yarn `>1.22.19`](https://classic.yarnpkg.com/en/docs/install/#mac-stable)


## Como rodar o projeto <a href='run-project'></a>

### baixe o arquiovo fiap-challenge.zip

### Front-end

1. rode `cd fiap-challenge-frontend`
2. Instale as dependências do projeto com o  `yarn`
3. Por fim, rode o projeto: `yarn dev`

### Back-end

O projeto back-end foi construido utilizando o framework NestJS e com Docker.
Para fazer funcionar faça os seguites passos:

1. Entra dentro da pasta do projeto `cd fiap-challenge-backend`
2. Rode o docker usando `make start` ou `docker-compose up -d`
3. Após subir a maquina docker, em outra aba é necessário subir o banco de dados e o seed
   1. `yarn prisma:db:push`
   2. `yarn prisma:db:seed`
4. Com isso, o projeto ja vai estar funcionando e integrado no front-end.

## Participantes <a href='participants'></a>
<p>Danielle Cavalcante Bevilaqua | 348330</p>
<p>Luan Verdelho de Freitas | 348041</p>
<p>Mario José de Souza Junior | 430102</p>
<p>Samuel de Araújo Santos | 348940</p>
