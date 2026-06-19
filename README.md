# Scripts do Projeto: PostgreSQL vs. Neo4j (TPC-H)

Este repositório contém os códigos-fonte utilizados no trabalho prático da disciplina de Administração de Banco de Dados. O objetivo do projeto foi testar e comparar o desempenho de consultas entre um banco relacional e um banco de dados orientado a grafos.

## 📂 O que tem neste repositório?

Aqui você encontrará exclusivamente as implementações das **22 consultas do benchmark TPC-H**, desenvolvidas em duas linguagens diferentes:

* **`SQL`**: Scripts criados para o **PostgreSQL 18.3**. Seguem o padrão relacional tradicional, com uso de cláusulas `JOIN` e funções de agregação (`SUM`, `AVG`, `COUNT`).
* **`Cypher`**: Scripts traduzidos para o **Neo4j 2.1.4**. Utilizam a abordagem de grafos, onde as tabelas e junções foram substituídas por nós, relacionamentos e travessias de caminhos.

*Nota: Todos os scripts foram projetados para rodar na massa de dados original fornecida pelo benchmark TPC-H, sem que os dados fossem regerados.*

## 👥 Autores do Projeto
* Pedro Henrique Peixoto Do Amaral
* Sarah Stephany da Cruz Souza Campos
