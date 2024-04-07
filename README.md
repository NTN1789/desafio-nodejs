# Desafio de Desenvolvimento de API de Agendamento

# Natan almeida da silva 


## Descrição do Projeto

O objetivo deste desafio é desenvolver uma API RESTful em Node.js utilizando TypeScript para um sistema de agendamento de salões de beleza. A API permitirá que os clientes do salão agendem serviços de beleza fornecendo apenas um e-mail de contato.

## Requisitos do Projeto

1. Implementar uma API RESTful em Node.js com TypeScript.
2. Utilizar um banco de dados relacional (por exemplo, MySQL, PostgreSQL, SQLite) para armazenar os dados dos agendamentos.
3. Criar endpoints para:
   - Listar todos os agendamentos.
   - Agendar um serviço de beleza, fornecendo apenas um e-mail de contato.
   - Cancelar um agendamento pelo ID.
4. Utilizar TypeScript para melhorar a robustez do código.

## Tecnologias Utilizadas

- Node.js
- TypeScript
- Express.js
- Banco de Dados Relacional (MySQL, PostgreSQL, SQLite, etc.)



## REST API


## Install

- Node.js
- TypeScript
- Express.js
- Sequelize
- Banco de Dados Relacional PostgreSQL  ou Docker 



## Start  do projeto 

- npm  run  start  ou npm run dev 


## Get agendamento 

 - http://localhost:8080/api/agendamento


 ## Response 

- HTTP/1.1 200 OK
- Date: Thu, 24 Feb 2011 12:36:30 GMT
- Status: 200 OK
- Connection: close
- []




## Post agendamento 

 - http://localhost:8080/api/agendamento


 ## Response 

- HTTP/1.1 200 OK
- email: "teste@gmail.com",
- nome: "teste",
- agendou: "opcional",
- Status: 200 OK,
- Connection: close
- []

## delete agendamento 

 - http://localhost:8080/api/agendamento/2


 ## Response 

- HTTP/1.1 200 OK,
- agendamento deletado ,
- Status: 200 OK,
- Connection: close,
- []
