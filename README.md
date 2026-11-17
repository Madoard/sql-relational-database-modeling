<div align="center">

  <p>｡ﾟ☁︎｡⋆｡ ﾟ☾ ﾟ｡⋆ ──────────── ꒰ 🗄️ ꒱ ──────────── ⋆｡ﾟ☾ ﾟ｡⋆｡☁︎｡ﾟ</p>

  <h1>˚₊‧꒰ა 🪻 Relational Database Modeling & SQL 🪻 ໒꒱‧₊˚</h1>

  <p>
    <i>✧･ﾟ: *✧･ﾟ:* Conceptual Entity-Relationship Modeling (ERM) and MySQL relational database implementation covering schema design, data population, and analytical queries *:･ﾟ✧*:･ﾟ✧</i>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Database-MySQL-FFB7C5?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/Modeling-Conceptual%20ERM-E6E6FA?style=for-the-badge&logoColor=555555" alt="Conceptual ERM" />
    <img src="https://img.shields.io/badge/SQL-DDL%20%7C%20DML%20%7C%20DQL-FFD1DC?style=for-the-badge&logoColor=white" alt="SQL" />
  </p>

</div>

<br/>

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🪞 ꒱ Stage 1 — Conceptual Modeling (`ERM`)

* **₊˚📎 Domain:** Corporate Industrial Management System (`Projects`, `Employees`, `Departments`, `Parts`, `Warehouses`, and `Suppliers`).
* **₊˚🧁 Artifacts:** Entity-Relationship Diagram defining entities, composite/multivalued attributes, cardinalities (`1:N`, `N:N`), Primary Keys (`PK`), and Foreign Keys (`FK`).

![Entity-Relationship Model](mer.diagram.jpg)

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🪷 ꒱ Stage 2 — Physical Implementation (`MySQL`)

* **₊˚📎 Domain:** IT Technical Assistance & Service Order Management (`Empresa` database).
* **₊˚🧁 Schema (`DDL`):** Creation of `Tecnico`, `Cliente`, `Servico`, `Finalizacao`, `OrdemServico`, and the associative table `OrdemServico_Servico` with `AUTO_INCREMENT`, `ENUM`, `NOT NULL`, and referential integrity constraints.
* **₊˚📎 Data Population (`DML`):** Structured `INSERT` scripts populating clients, technicians, service catalogs, completed orders, and open/in-progress tickets.
* **₊˚🧁 Analytical Queries (`DQL`):** Business reports using `COUNT`, `WHERE`, `ORDER BY`, `INNER JOIN`, `GROUP BY`, and `SUM`.

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 📂 ꒱ Repository Files

| File | Vibe | Description |
| :--- | :---: | :--- |
| `database_service_orders.sql` | 🪻 | Complete MySQL script (`CREATE DATABASE`, `CREATE TABLE`, `INSERT INTO`, and `SELECT` queries) in Portuguese |
| `mer.diagram.jpg` | 🪞 | Conceptual Entity-Relationship Diagram |

<br/>

<div align="center">
  <p>°•. 🪻 .•° ────── ꒰ 💗 ꒱ ────── °•. 🪻 .•°</p>
  <p><i>made with 💗 by <b>Maria Eduarda Gonçalves</b></i></p>
</div>
