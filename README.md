<div align="center">

  <p>｡ﾟ☁︎｡⋆｡ ﾟ☾ ﾟ｡⋆ ──────────── ꒰ 🗄️ ꒱ ──────────── ⋆｡ﾟ☾ ﾟ｡⋆｡☁︎｡ﾟ</p>

  <h1>˚₊‧꒰ა 🪻 Modelagem de Banco de Dados Relacional & SQL 🪻 ໒꒱‧₊˚</h1>

  <p>
    <i>✧･ﾟ: *✧･ﾟ:* Modelagem Conceitual Entidade-Relacionamento (MER) e implementação de banco de dados relacional em MySQL cobrindo desenho de schema, população de dados e consultas analíticas *:･ﾟ✧*:･ﾟ✧</i>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Banco%20de%20Dados-MySQL-FFB7C5?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/Modelagem-MER%20Conceitual-E6E6FA?style=for-the-badge&logoColor=555555" alt="MER Conceitual" />
    <img src="https://img.shields.io/badge/SQL-DDL%20%7C%20DML%20%7C%20DQL-FFD1DC?style=for-the-badge&logoColor=white" alt="SQL" />
  </p>

</div>

<br/>

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🪞 ꒱ Etapa 1 — Modelagem Conceitual (`MER`)

- **₊˚📎 Domínio:** Sistema de Gestão Industrial Corporativa (`Projetos`, `Funcionários`, `Departamentos`, `Peças`, `Almoxarifados` e `Fornecedores`).
- **₊˚🧁 Artefatos:** Diagrama Entidade-Relacionamento definindo entidades, atributos compostos/multivalorados, cardinalidades (`1:N`, `N:N`), Chaves Primárias (`PK`) e Chaves Estrangeiras (`FK`).

![Modelo Entidade-Relacionamento](mer.diagram.jpg)

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 🪷 ꒱ Etapa 2 — Implementação Física (`MySQL`)

- **₊˚📎 Domínio:** Assistência Técnica de TI e Gestão de Ordens de Serviço (banco `Empresa`).
- **₊˚🧁 Estrutura / Schema (`DDL`):** Criação das tabelas `Tecnico`, `Cliente`, `Servico`, `Finalizacao`, `OrdemServico` e da tabela associativa `OrdemServico_Servico` com `AUTO_INCREMENT`, `ENUM`, `NOT NULL` e restrições de integridade referencial.
- **₊˚📎 População de Dados (`DML`):** Scripts estruturados de `INSERT` populando clientes, técnicos, catálogo de serviços, ordens concluídas e chamados abertos/em andamento.
- **₊˚🧁 Consultas Analíticas (`DQL`):** Relatórios de negócio utilizando `COUNT`, `WHERE`, `ORDER BY`, `INNER JOIN`, `GROUP BY` e `SUM`.

<p align="center">‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾. ─────────────────────── ‧₊˚ ☁️⋅♡𓂃 ࣪ ִֶָ☾.</p>

### ╰┈➤ ꒰ 📂 ꒱ Arquivos do Repositório

| Arquivo | Vibe | Descrição |
| :--- | :---: | :--- |
| `database_service_orders.sql` | 🪻 | Script completo em MySQL (`CREATE DATABASE`, `CREATE TABLE`, `INSERT INTO` e consultas `SELECT`) em português |
| `mer.diagram.jpg` | 🪞 | Diagrama Conceitual Entidade-Relacionamento |

<br/>

<div align="center">
  <p>°•. 🪻 .•° ────── ꒰ 💗 ꒱ ────── °•. 🪻 .•°</p>
  <p><i>feito com 💗 por <b>Maria Eduarda Gonçalves</b></i></p>
</div>
