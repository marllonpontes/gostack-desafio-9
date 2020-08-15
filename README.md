<div align="center">
  <img alt="GoStack"
    src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png"
  />
</div>

<h2 align="center">
  Desafio 08: Fundamentos do React Native
</h2>

<p align="center">
  <img alt="language version" src="https://img.shields.io/badge/React%20Native-v_0.62.1-339933?logo=react">
  <img alt="language version" src="https://img.shields.io/badge/Yarn-v_1.22.4-2C8EBB?logo=Yarn">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/marllonpontes/gostack-desafio-4">
</p>

<hr/>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-execute-o-projeto">Execute o projeto</a>
</p>

## :rocket: Sobre o desafio
Nesse desafio, desenvolverá uma nova aplicação, a GoMarketplace. Dessa vez é hora de você praticar o que você aprendeu até agora no React Native, junto com TypeScript, utilizando rotas, Async Storage e a Context API.

## 🔥 Funcionalidades

Neste projeto, as rotas foram implementadas usando métodos HTTP:
- **`Listar os produtos da fake API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem através de uma tabela, com o campo `title`, `image_url` e `price`.

- **`Adicionar itens ao carrinho`**: Em toda sua aplicação, você deve utilizar o Contexto chamado `cart` que deixamos disponível. Você vai precisar completar as funcionalidades dentro de `hooks/cart.tsx` para que você consiga adicionar itens ao carrinho.

- **`Exibir itens do carrinho`**: Na página `Cart` você deve exibir todos os itens do carrinho, junto com a quantidade, valor único, valor subtotal dos itens e total de todos os items.

- **`Aumentar quantidade de itens do carrinho`**: Na página `Cart` você deve permitir que o usuário aumente a quantidade de itens do mesmo produto, para isso você pode utilizar a função `increment` dentro do seu contexto em `/src/hooks/cart.tsx`.

- **`Diminuir quantidade de um item do carrinho`**: Na página `Cart` você deve permitir que o usuário decremente a quantidade de itens do mesmo produto, para isso você pode utilizar a função `decrement` dentro do seu contexto em `/src/hooks/cart.tsx`.

- **`Exibir valor total dos itens no carrinho`**: Tanto na página `Dashboard`, tanto na página `Cart` você deve exibir o valor total de todos os itens que estão no seu carrinho.

## ⚙ Tecnologias

* __React Native__
* Yarn
* Jest

## :computer: Execute o projeto

Clone este repositório:

```bash
$ git clone https://github.com/marllonpontes/gostack-desafio-8
```

Mova-se para diretório da aplicação:

```bash
$ cd gostack-desafio-8
```

Para instalar as dependências execute:

```bash
yarn install
```

E para iniciar o app:

```bash
react-native run-android
```

<br/>
