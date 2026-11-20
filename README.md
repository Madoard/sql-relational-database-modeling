<div align="center">

  <p>─────────────────────── ✦ ───────────────────────</p>

  <h1>˚₊‧꒰ა Modelagem de Banco de Dados Relacional & SQL ໒꒱‧₊˚</h1>

  <p>
    <i>Modelagem Conceitual Entidade-Relacionamento (MER) e implementação em MySQL com criação de schema, carga de dados e consultas analíticas.</i>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Banco%20de%20Dados-MySQL-FFB7C5?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    <img src="https://img.shields.io/badge/Modelagem-MER%20Conceitual-E6E6FA?style=for-the-badge&logoColor=555555" alt="MER Conceitual" />
    <img src="https://img.shields.io/badge/SQL-DDL%20%7C%20DML%20%7C%20DQL-FFD1DC?style=for-the-badge&logoColor=white" alt="SQL" />
  </p>

</div>

<br/>

### ✦ Resumo

Reúne duas etapas de banco de dados: o desenho conceitual de um sistema de gestão industrial corporativa em Modelo Entidade-Relacionamento (`MER`) e a implementação física em MySQL para assistência técnica de TI e ordens de serviço (`Empresa`).

### ✦ Tecnologias

- **MySQL & SQL (`DDL`, `DML`, `DQL`):** Definição de tabelas e relacionamentos, inserção de registros e consultas com `COUNT`, `WHERE`, `ORDER BY`, `INNER JOIN`, `GROUP BY` e `SUM`.
- **Modelagem Conceitual (`MER`):** Estruturação de entidades, atributos, cardinalidades (`1:N` e `N:N`), chaves primárias (`PK`) e chaves estrangeiras (`FK`).

### ✦ Regras

#### Etapa 1 — Modelagem Conceitual (`MER`)

- **Domínio:** Gestão industrial corporativa envolvendo `Projetos`, `Funcionários`, `Departamentos`, `Peças`, `Almoxarifados` e `Fornecedores`.
- **Regras de modelagem:** Definição de chaves primárias e estrangeiras, cardinalidades entre entidades e atributos organizados no diagrama conceitual.

#### Etapa 2 — Implementação Física (`MySQL`)

- **Domínio:** Assistência técnica de TI e gestão de ordens de serviço no banco `Empresa`.
- **Estrutura e integridade:** Tabelas `Tecnico`, `Cliente`, `Servico`, `Finalizacao`, `OrdemServico` e `OrdemServico_Servico` com `AUTO_INCREMENT`, `ENUM`, `NOT NULL` e vínculos de integridade referencial.
- **População e consultas:** Carga de clientes, técnicos, serviços e ordens (concluídas e em aberto/andamento), seguida de consultas analíticas de acompanhamento e faturamento.
<p align="center">─────────────────────── · ───────────────────────</p>

<p align="center">─────────────────────── · ───────────────────────</p>

### ✦ Como Executar

1. **Pré-requisitos:** Tenha o **MySQL Server** (ou cliente MySQL) instalado e em execução.
2. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Madoard/sql-relational-database-modeling.git](https://github.com/Madoard/sql-relational-database-modeling.git)
   cd sql-relational-database-modeling
   ```
3. **Execute o script SQL (`serviço-de-ordens-do-banco-de-dados.sql`):**
   ```bash
   mysql -u seu_usuario -p < serviço-de-ordens-do-banco-de-dados.sql
   ```

### ✦ Exemplo de Uso

```text
+---------------+
| TotalServicos |
+---------------+
|            10 |
+---------------+

+---------------------+------------+------------+
| dataAbertura        | equipamento| prioridade |
+---------------------+------------+------------+
| 2026-02-11 14:10:00 | Notebook   | Média      |
| 2026-02-13 13:35:00 | Desktop    | Baixa      |
| 2026-02-14 10:10:00 | Notebook   | Média      |
| 2026-02-15 09:00:00 | Notebook   | Média      |
| 2026-02-15 11:20:00 | Notebook   | Alta       |
| 2026-02-15 16:30:00 | Desktop    | Média      |
+---------------------+------------+------------+

+---------+---------+--------------+
| idOrdem | idOrdem | ValorTotalOS |
+---------+---------+--------------+
|       7 |       7 |       400.00 |
|       5 |       5 |       350.00 |
|      20 |      20 |       350.00 |
|      17 |      17 |       300.00 |
+---------+---------+--------------+
```

<p align="center">─────────────────────── · ───────────────────────</p>

### ✦ Como Foi Construído

- **Modelagem Conceitual (`MER`):** Definição das entidades, atributos, cardinalidades (`1:N` e `N:N`), chaves primárias (`PK`) e chaves estrangeiras (`FK`) no diagrama conceitual (`mer.diagrama.jpg`).
- **Estrutura e Carga em MySQL (`DDL` e `DML`):** Criação do banco `Empresa` e das tabelas `Tecnico`, `Cliente`, `Servico`, `Finalizacao`, `OrdemServico` e `OrdemServico_Servico` em [`serviço-de-ordens-do-banco-de-dados.sql`](./serviço-de-ordens-do-banco-de-dados.sql), com restrições `NOT NULL`, `ENUM`, `AUTO_INCREMENT`, chaves estrangeiras e inserts iniciais.
- **Consultas Analíticas (`DQL`):** Elaboração de consultas com `COUNT`, `WHERE`, `ORDER BY`, `JOIN`, `GROUP BY` e `SUM` para contagem de serviços, listagem de ordens abertas, cálculo de subtotais e consolidação do valor por ordem de serviço.

### ✦ Arquivos do Repositório

| Arquivo | Descrição |
| :--- | :--- |
| [`serviço-de-ordens-do-banco-de-dados.sql`](./serviço-de-ordens-do-banco-de-dados.sql) | Script completo em MySQL com criação do banco/tabelas (`DDL`), inserção de dados (`DML`) e consultas (`DQL`) |
| [`mer.diagrama.jpg`](./mer.diagrama.jpg) | Diagrama Conceitual Entidade-Relacionamento (`MER`) |

<br/>

<div align="center">
  <p>°•. ✦ .•° ────── ꒰ ✦ ꒱ ────── °•. ✦ .•°</p>
  <p><i>Feito por <b>Eduarda Gonçalves</b></i></p>
</div>
