📘 Projeto Livraria Saber — Scripts SQL

Este repositório contém os arquivos SQL desenvolvidos para a disciplina Modelagem e Manipulação de Dados, utilizando MySQL, com objetivo de criar, popular e consultar um banco de dados completo baseado no mini-mundo de uma livraria e papelaria.
Inclui comandos de criação de tabelas, inserção de dados, consultas, atualizações e exclusões.

📁 Estrutura do Repositório
├── 01_create_tables.sql      -> Criação das tabelas
├── 02_insert.sql             -> Inserção dos dados
├── 03_select.sql             -> Consultas SELECT
├── 04_update_delete.sql      -> Comandos UPDATE e DELETE
└── README.md                 -> Documentação geral

🗂️ Descrição dos Arquivos
01_create_tables.sql

Contém os comandos SQL responsáveis pela criação de todas as tabelas do banco de dados Livraria Saber.
Inclui definição de chaves primárias, estrangeiras, relacionamentos e tipos de dados.

02_insert.sql

Script responsável pela população inicial das tabelas:

Cliente

Vendedor

Fornecedor

Autor

Editora

Livro

Papelaria

Livro_Autor (tabela de relacionamento N:N)

Venda

Item_Venda

Os dados foram criados de forma coerente com o mini-mundo proposto.

03_select.sql

Contém diversas consultas SQL utilizando:

WHERE

LIKE

ORDER BY

JOIN

GROUP BY

LIMIT

As consultas permitem visualizar de forma clara clientes, vendas, livros, itens de venda, produtos de papelaria, autores e editoras.

04_update_delete.sql

Inclui comandos:

UPDATE (edição e correção de registros)

DELETE (remoção segura de dados com condições)

Todos os comandos respeitam as restrições de integridade referencial do banco.

🛠️ dump_livraria.sql (Opcional)

Caso exista, este arquivo contém o backup completo gerado pelo MySQL Workbench, permitindo recriar todo o banco em outro ambiente.

💻 Tecnologias Utilizadas

MySQL Server

MySQL Workbench

VS Code

Git & GitHub

▶️ Como Executar os Arquivos
1. Criar o Banco de Dados

No MySQL Workbench:

CREATE DATABASE livraria_saber;
USE livraria_saber;

2. Executar na Ordem Correta

1️⃣ Rodar 01_create_tables.sql
2️⃣ Rodar 02_insert.sql
3️⃣ Rodar 03_select.sql (para testar consultas)
4️⃣ Rodar 04_update_delete.sql (opcional)