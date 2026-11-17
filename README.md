# sql-relational-database-modeling
⋆｡ﾟ☁︎｡⋆｡ ﾟ☾ ﾟ｡⋆ ────── ꒰ 🗄️ ꒱ ────── ⋆｡ﾟ☾ ﾟ｡⋆｡☁︎｡⋆

# ˚₊‧꒰ა 🌸 Relational Database Modeling & SQL 🌸 ໒꒱‧₊˚

> ✧･ﾟ: *✧･ﾟ:* Conceptual Entity-Relationship Modeling (ERM) and MySQL relational database implementation covering schema design, data population, and analytical queries. *:･ﾟ✧*:･ﾟ✧

‧₊˚ ⋅ ─────────────────────── ⋅ ˚₊‧

## ꒰ 🦢 ꒱ Project Structure

This repository is divided into two main stages of database engineering:

### Stage 1 — Conceptual Modeling (`ERM`)
* ₊˚⊹ **Domain:** Corporate Industrial Management System (`Projects`, `Employees`, `Departments`, `Parts`, `Warehouses`, and `Suppliers`).
* ₊˚⊹ **Artifacts:** Entity-Relationship Diagram defining entities, composite/multivalued attributes, cardinalities (`1:N`, `N:N`), Primary Keys (`PK`), and Foreign Keys (`FK`).
* ₊˚⊹ **Diagram:** *
* ![Entity-Relationship Model](mer.diagram.jpg)

### Stage 2 — Physical Implementation (`MySQL`)
* ₊˚✧ **Domain:** IT Technical Assistance & Service Order Management (`Empresa` database).
* ₊˚✧ **Schema (`DDL`):** Creation of `Tecnico`, `Cliente`, `Servico`, `Finalizacao`, `OrdemServico`, and the associative table `OrdemServico_Servico` with `AUTO_INCREMENT`, `ENUM`, `NOT NULL`, and referential integrity constraints.
* ₊˚✧ **Data Population (`DML`):** Structured `INSERT` scripts populating clients, technicians, service catalogs, completed orders, and open/in-progress tickets.
* ₊˚✧ **Analytical Queries (`DQL`):** Business reports using `COUNT`, `WHERE`, `ORDER BY`, `INNER JOIN`, `GROUP BY`, and `SUM`.

‧₊˚ ⋅ ─────────────────────── ⋅ ˚₊‧

## ꒰ 🎀 ꒱ Files in This Repository

* ₊˚⊹ `database_service_orders.sql` — Complete MySQL script (`CREATE DATABASE`, `CREATE TABLE`, `INSERT INTO`, and `SELECT` queries) in Portuguese.
* ₊˚⊹ `mer-diagram.png` — Conceptual Entity-Relationship Diagram.

°•. ✿ .•° ────── ꒰ 🎀 ꒱ ────── °•. ✿ .•°

*made with 💗 by **Maria Eduarda Gonçalves***
