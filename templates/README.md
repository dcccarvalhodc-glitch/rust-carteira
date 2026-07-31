# Carteira de Investimentos Fullstack com Rust

## Sobre o projeto

Este projeto foi desenvolvido como parte do desafio da DIO utilizando Rust.

A aplicação permite o cadastro e autenticação de usuários, além do gerenciamento de ativos de investimento. Os dados são armazenados em um banco PostgreSQL e a interface web foi desenvolvida utilizando Askama.

## Tecnologias utilizadas

- Rust
- Axum
- SQLx
- PostgreSQL
- Askama
- Docker

## Como executar

1. Inicie o banco de dados PostgreSQL.
2. Execute as migrações:

```bash
sqlx migrate run
```

3. Execute a aplicação:

```bash
cargo run
```

4. Acesse no navegador:

```
http://localhost:3000
```

## Melhoria implementada

Foi criada uma página inicial (dashboard) para a pessoa usuária após o login.

Na versão original do projeto era exibida apenas uma mensagem simples de boas-vindas. Nesta versão, o dashboard apresenta uma tela mais amigável, exibindo o nome do usuário autenticado e informações básicas sobre a aplicação.

## Como testar

- Execute a aplicação com `cargo run`;
- Acesse `http://localhost:3000`;
- Faça login ou cadastre um novo usuário;
- Após a autenticação, será exibido o dashboard personalizado.

## O que aprendi

Durante este desafio aprendi a:

- configurar o ambiente de desenvolvimento em Rust;
- utilizar SQLx com PostgreSQL;
- executar migrações do banco de dados;
- trabalhar com autenticação utilizando cookies e JWT;
- criar páginas HTML utilizando Askama;
- realizar pequenas melhorias em uma aplicação Fullstack.
## Imagens da aplicação

### Tela de Login

![Tela de Login](images/login.png)

### Dashboard

![Dashboard](images/dashboard.png)