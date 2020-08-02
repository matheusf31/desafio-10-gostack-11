<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 10: GoRestaurant Web
</h3>

<blockquote align="center">“O tempo que leva para realizar seus sonhos vai passar de qualquer forma”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%2304D361">
  </a>

  <a href="https://github.com/Rocketseat/bootcamp-gostack-desafios/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rocketseat/bootcamp-gostack-desafios?style=social">
  </a>
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, desenvolvi mais uma aplicação, a GoRestaurant. Pratiquei o que aprendi até agora no React.js junto com TypeScript, aplicando o conceito de CRUD (Create, Read, Update, Delete).

Essa é uma aplicação que se conecta a uma fake API, e exibe os pratos de comida criados e permite a criação, remoção e atualização desses pratos.

[Link do desafio](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-reactjs-crud)

### Utilizando uma fake API

Antes de tudo, para que você tenha os dados para exibir em tela, deixei um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, deixei instalado no seu package.json uma dependência chamada `json-server`, e um arquivo chamado `server.json` que contém os dados para uma rota `/foods`. Para executar esse servidor você pode executar o seguinte comando:

```js
  yarn json-server server.json -p 3333
```

### Layout da aplicação

Essa aplicação possui um layout disponibilizado pela Rocketseat.

O layout pode ser acessado através da página do Figma, no [seguinte link](https://www.figma.com/file/1lK6AVCPybtWeBLCH8B08N/GoRestaurant?node-id=0%3A1).

Você precisará de uma conta (gratuita) no Figma para inspecionar o layout e obter detalhes de cores, tamanhos, etc.

### Funcionalidades da aplicação

- **`Listar os pratos de comida da API`**: A página `Dashboard` é capaz de exibir uma listagem, com o campo `title`, `value`, e  `description` e `available` de todos os pratos de comida que estão cadastrados na API.

**Dica**: Para exibir se o prato de comida está disponível ou não, o campo `available` é retornado da API e é exibido `Disponível` caso seja true, e `Indisponível` caso seja false.

- **`Adicionar novos pratos de comida na API`**: No Dashboard um modal é aberto ao clicar no botão `Novo Prato` no Header. Esse modal é responsável por cadastrar uma nova `food` passando os campos `image`, `name`, `description`, `value`.

- **`Editar pratos de comida da sua API`**: Na página Dashboard outro modal é aberto ao clicar no botão `Editar Prato`. Esse modal é responsável por editar uma `food` passando os campos `image`, `name`, `description`, `value`.

- **`Remover pratos de comida da sua API`**: No Dashboard é possível remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

- **`Alterar disponibilidade dos pratos de comida da sua API`**: No Dashboard você pode alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.

---

Feito com 💜 by Me :wave:
