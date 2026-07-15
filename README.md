# Aula 01 - Criação do Ambiente (SQL Server)

## Objetivo

Nesta aula foram estudados os comandos fundamentais para criação e configuração de um banco de dados no SQL Server.

O objetivo é compreender como criar um banco de dados, definir tabelas, relacionamentos, restrições e regras de integridade, que são a base para qualquer sistema de informação e para projetos de Business Intelligence (BI).

---

## Conteúdo estudado

* Criação e exclusão de banco de dados (`CREATE DATABASE` e `DROP DATABASE`)
* Seleção do banco de dados (`USE`)
* Criação de tabelas (`CREATE TABLE`)
* Tipos de dados (`INT`, `CHAR`, `VARCHAR`, `NUMERIC`, `DATETIME`)
* Colunas auto incrementais (`IDENTITY`)
* Chaves Primárias (`PRIMARY KEY`)
* Chaves Estrangeiras (`FOREIGN KEY`)
* Restrições de unicidade (`UNIQUE`)
* Valores padrão (`DEFAULT`)
* Restrições de validação (`CHECK`)
* Alteração de tabelas (`ALTER TABLE`)
* Colunas calculadas
* Relacionamentos entre tabelas
* Índices `CLUSTERED` e `NONCLUSTERED`
* Comandos `PRINT`, `NEWID()` e `GO`

---

## Estrutura do banco de dados

O banco de dados criado possui as seguintes tabelas:

* UFS
* CIDADES
* BAIRROS
* LOGRADOUROS
* CLIENTES
* PRODUTOS
* VENDAS
* ITENS_VENDAS

Essas tabelas estão relacionadas através de chaves estrangeiras, garantindo a integridade dos dados.

---

## Principais conceitos aprendidos

Durante esta aula compreendi a importância de:

* Criar bancos de dados de forma organizada.
* Definir corretamente os tipos de dados.
* Utilizar chaves primárias para identificar registros.
* Relacionar tabelas utilizando chaves estrangeiras.
* Garantir a qualidade dos dados através das constraints (`PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `CHECK` e `DEFAULT`).
* Utilizar colunas calculadas para automatizar cálculos.
* Entender a função dos índices para melhorar o desempenho das consultas.

---

## Objetivo do estudo

Meu foco nesta aula é entender o funcionamento de cada comando SQL, compreender sua finalidade e saber em quais situações ele é utilizado na prática.

Mais importante do que decorar a sintaxe é desenvolver uma base sólida em Banco de Dados para aplicação futura em projetos de Análise de Dados, Business Intelligence (BI) e Data Warehouse.

---

## Arquivos desta aula

* `CriacaoDoAmbiente.sql` — Script completo de criação do banco de dados e das tabelas.

---

## Próximos passos

Após dominar os conceitos desta aula, pretendo estudar:

* INSERT
* UPDATE
* DELETE
* SELECT
* WHERE
* ORDER BY
* GROUP BY
* JOINs
* Views
* Procedures
* Funções

---
