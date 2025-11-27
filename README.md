Aqui está a versão completa em texto (Markdown). Você pode copiar tudo o que está dentro do bloco de código abaixo e colar direto no seu arquivo `README.md` no VS Code.

Quando você subir para o GitHub, ele vai ficar formatado e organizado exatamente como você quer (com a árvore de arquivos alinhada).

````markdown
# Projeto Arena Legends – Scripts SQL

Este repositório contém os arquivos SQL desenvolvidos para a Experiência Prática de Modelagem e Manipulação de Dados, utilizando MySQL como sistema gerenciador de banco de dados. O projeto implementa a criação, povoamento e manipulação de dados de um sistema de gestão para um jogo online competitivo (MOBA).

## Estrutura do Repositório

```text
Projeto ArenaLegends
├── 📂 01_create_tables.sql ...... Criação das tabelas
├── 📂 02_insert_data.sql ........ Inserts de dados
├── 📂 03_select_queries.sql ..... Consultas SQL
├── 📂 04_update_delete.sql ...... Updates e Deletes
└── 💾 arenalegends.sql .......... Backup completo do banco
````

## Descrição dos Arquivos

### 01\_create\_tables.sql

Contém os comandos SQL responsáveis pela criação das tabelas do banco de dados `arena_legends`. Inclui definição de campos, tipos de dados, chaves primárias e estrangeiras.

### 02\_insert\_data.sql

Script de inserção de dados iniciais nas tabelas:

  * **Jogador**
  * **Personagem (Herói)**
  * **Item (Skin/Equipamento)**
  * **Partida**
  * **Guilda**

Esses dados são utilizados para testes e validação das consultas.

### 03\_select\_queries.sql

Contém diversas consultas SQL utilizando:

  * WHERE
  * ORDER BY
  * JOIN
  * GROUP BY

Demonstra domínio da DML para recuperação e manipulação de dados (ex: Ranking de jogadores, histórico de partidas).

### 04\_update\_delete.sql

Inclui comandos de:

  * **UPDATE** (três atualizações específicas, ex: alteração de saldo ou nível)
  * **DELETE** (três exclusões controladas)

Todos os comandos respeitam a integridade referencial do banco.

### arenalegends.sql

Arquivo completo gerado pelo MySQL Workbench contendo:

  * Estrutura do banco
  * Dados já inseridos
  * Modificações e operações realizadas

Serve como backup completo e pode ser utilizado para restaurar o projeto em outro ambiente.

## Tecnologias Utilizadas

  * MySQL Server
  * MySQL Workbench
  * VS Code
  * GitHub

## Como Executar os Arquivos

### 1\. Criar o Banco de Dados

No MySQL Workbench ou terminal:

```sql
CREATE DATABASE arena_legends;
USE arena_legends;
```

```
```