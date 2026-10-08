# PizzaEsabor
# 🍕 Banco de Dados — Pizzaria

## 📌 Descrição

Este projeto consiste na criação de um banco de dados relacional para uma pizzaria.

O banco foi desenvolvido para organizar e armazenar informações sobre clientes, pizzas, funcionários, pedidos, pagamentos e entregas.

## 🎯 Objetivo

O objetivo do projeto é melhorar a organização das informações da pizzaria, reduzindo erros, perda de dados e dificuldades no controle dos pedidos.

## 🗄️ Estrutura do Banco de Dados

O banco de dados possui 7 tabelas:

* `clientes` — armazena os dados dos clientes.
* `pizzas` — armazena os sabores, tamanhos e preços das pizzas.
* `funcionarios` — armazena os dados dos funcionários.
* `pedidos` — registra os pedidos realizados pelos clientes.
* `itens_pedido` — relaciona os pedidos com as pizzas.
* `pagamentos` — registra os pagamentos dos pedidos.
* `entregas` — registra as informações das entregas.

## 🔗 Relacionamentos

* `clientes` → `pedidos` — 1:N
* `pedidos` → `itens_pedido` — 1:N
* `pizzas` → `itens_pedido` — 1:N
* `pedidos` → `pagamentos` — 1:1
* `pedidos` → `entregas` — 1:1
* `funcionarios` → `entregas` — 1:N

## 💻 Tecnologias utilizadas

* MySQL
* MySQL Workbench
* SQL
* Aiven
* Git
* GitHub

## 📊 Consultas SQL

O projeto possui 10 consultas SQL utilizando recursos como:

* `SELECT`
* `WHERE`
* `LIKE`
* `INNER JOIN`
* `GROUP BY`
* `ORDER BY`
* `BETWEEN`
* `SUM`
* `COUNT`

As consultas foram desenvolvidas para responder situações relacionadas ao funcionamento da pizzaria.

## ☁️ Hospedagem

O banco de dados foi preparado para ser hospedado na plataforma Aiven, utilizando um serviço MySQL na nuvem.

## 💾 Dump

Foi utilizado o `mysqldump` para realizar o backup do banco de dados, incluindo sua estrutura e seus dados.

## 📁 Arquivos do projeto

```text
pizzaria/
│
├── README.md
│
└── sql/
    ├── banco_pizzaria.sql
    ├── inserts.sql
    └── consultas.sql
```

## 👨‍💻 Autor

**Alisson Magalhães dos Santos**

Projeto desenvolvido para fins acadêmicos.
