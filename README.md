# GOStack desafio 06

Uma aplicação para armazenar transações financeiras de entrada e saída, que deve permitir o cadastro e a listagem dessas transações através de um arquivo csv.

[![node version](https://img.shields.io/node/v/react)](https://img.shields.io/node/v/node)
![npm](https://img.shields.io/npm/v/pg?label=Postgres)
![npm](https://img.shields.io/npm/v/typeorm?label=typeorm)
<img src="https://img.shields.io/github/languages/top/tsunodajapa/gostack_desafio_06">

Este desafio tem como objetivo utilizar alguns apredizados no módulo 2 parte 2 do Gostack.
Um upgrade do desafio 05, onde além de cadastro de transações, agora também é possível receber um arquivo csv através da rota para realizar o cadastro. 

## Aplicações
- [X] No cadastro não é possível fazer uma transação de saída se o saldo for menor do que o valor da transação;
- [X] Deve ser possível listar todas transações;
- [X] Ao listar as transações, deve retornar o total de transações de saída e entrada, além do saldo atual (foi utlizado reduce);
- [X] Deve ser possível cadastrar transações a partir de um arquivo csv

## Conceitos estudados

- Conceitos avançados de SOLID;
- Criação de Repositórios, Entidades, Services (SOLID);
- Typeorm com banco postgres
- Migrations
- receber arquivos através das rotas usando multer
- importar arquivos csv através do csv-parse

## Requisitos de instalação

- npm >= 6.0.0
- node >= 10
- Banco de Dados Postgres

## Como utilizar

#### Atualize o arquivo ormconfig.json com os dados do seu banco.

#### Execute o comando para instalações de dependências do servidor:

```
yarn
```

#### Iniciar o servidor:
```
yarn dev:server
```




