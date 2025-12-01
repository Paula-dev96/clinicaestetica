# 🏥 Banco de Dados -- Clínica de Estética

Este projeto apresenta a modelagem e implementação de um banco de dados
para uma *clínica de estética*, incluindo MER, DER, criação das
tabelas e comandos SQL básicos.

## 📌 Objetivo

Criar um banco de dados organizado para controlar:

-   Clientes
-   Profissionais
-   Procedimentos
-   Agendamentos
-   Pagamentos

## 🧩 Modelagem do Banco

### MER -- Modelo Entidade-Relacionamento

Entidades principais: - Cliente - Profissional - Procedimento -
Agendamento - Pagamento

### DER -- Diagrama

Adicione sua imagem no caminho abaixo:

![DER](imagens/der.png)

## 🛠 Estrutura das Tabelas

### Cliente

-   id_cliente (PK)
-   nome
-   telefone
-   email

### Profissional

-   id_profissional (PK)
-   nome
-   especialidade

### Procedimento

-   id_procedimento (PK)
-   nome
-   descricao
-   valor

### Agendamento

-   id_agendamento (PK)
-   id_cliente (FK)
-   id_profissional (FK)
-   id_procedimento (FK)
-   data
-   hora

### Pagamento

-   id_pagamento (PK)
-   id_agendamento (FK)
-   valor
-   forma_pagamento

## 💾 Scripts SQL

### Criação das tabelas (DDL)

Exemplo:

 sql
CREATE TABLE cliente (...);


### Inserções (DML)

Exemplo:

 sql
INSERT INTO cliente (...) VALUES (...);


## 🔎 Consultas

-   Listar agendamentos com nome do cliente
-   Filtrar procedimentos
-   Consultar pagamentos
-   Ver agenda do profissional

## 📚 Tecnologias

-   SQL
-   Draw.io / DB Designer
-   MySQL / PostgreSQL / SQL Server

## 📝 Autora

Paula Nunes
