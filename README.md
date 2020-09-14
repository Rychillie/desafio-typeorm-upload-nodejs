<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
    Desafio 05: Primeiro projeto Node.js
</h3>

<p align="center">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/eduaugustus/desafio-gostack-conceitos-nodejs?color=%2304D361">
    <a href="https://rocketseat.com.br">
        <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rychillie-%2304D361">
    </a>
</p>

# 🚀 Sobre o Desafio:

Neste desafio eu apliquei um pouco dos conhecimentos de NodeJS que obtive no Bootcamp GoStack da RocketSeat para a criação de uma logica de transação em sistema de gastos.

# 🔧 Como testar a API criada:

- Clone este repositório no seu computador
- Com o projeto aberto você deve rodar os seguintes comandos em seu terminal para instalar as dependencias:

```shell
    yarn install / npm install
```

- Para iniciar a API você deve realizar o seguinte comando:

```shell
    yarn dev:server / npm run dev:server
```

- Para realizar testes na API:

```shell
    yarn test / npm run test
```

# 🛣️ Rotas para testar a API:

- **`POST - /transactions`** : Cria uma transação.

Para criar um recebimento:

```json
{
  "title": "Salario",
  "value": 1000,
  "type": "income"
}
```

Para criar uma retirada:

```json
{
  "title": "Patinete",
  "value": 499,
  "type": "outcome"
}
```

- **`GET - /transactions`** : Retorna todas transações.

---

Estudo feito por [Rychillie](https://rychillie.net)
