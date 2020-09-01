<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 10: GoRestaurant Web
</h3>

<p align="center">
<a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%2304D361">
  </a>

### :rocket: About the challenge

In this challenge, another application was developed, GoRestaurant. A way to practice what was learned in React.js together with TypeScript, practicing the concept of CRUD (Create, Read, Update, Delete).

This will be an application that will connect to a fake API, and display the created food dishes and allow the creation, removal and updating of these dishes.

### Using a fake API


First of all, so that you have the data to display on screen, we created a file that you can use as a fake API to provide you with this data.

For that, we leave a dependency called `json-server` installed in your package.json, and a file called` server.json` that contains the data for a `/ foods` route. To run this server you can run the following command:

```js
  yarn json-server server.json -p 3333
```
