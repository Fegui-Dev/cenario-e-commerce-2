# 🚗 Projeto Banco de Dados para Oficina Mecânica

Este repositório contém o projeto completo de modelagem lógica e implementação de um banco de dados para uma **oficina mecânica**, seguindo as diretrizes propostas no desafio do módulo de modelagem de banco de dados.

---

## 🛠️ Etapas do Projeto

### 1. Modelagem Conceitual
A modelagem foi feita com base em um modelo Entidade-Relacionamento (ER), e contempla:

- Clientes
- Veículos
- Ordens de Serviço
- Serviços realizados
- Funcionários
- Peças utilizadas
- Fornecedores

### 2. Esquema Lógico
O modelo lógico foi traduzido para SQL, respeitando:

- **Chaves primárias e estrangeiras**
- **Constraints de integridade**
- **Relacionamentos 1:N e N:N**
- **Normalização** para evitar redundâncias

### 3. Criação do Banco de Dados (Script SQL)
Um script `.sql` está incluso no projeto com os comandos de:
- Criação de tabelas
- Inserção de dados fictícios
- Constraints (PK, FK, UNIQUE, NOT NULL)

### 4. Consultas SQL Avançadas
Incluí diversas queries com foco em:

- `SELECT`, `WHERE`, `ORDER BY`
- `HAVING`, `JOIN`, `GROUP BY`
- Atributos derivados (ex: total de serviços por cliente)
- Relações entre serviços, peças e funcionários

#### Exemplo de perguntas respondidas:
- Quais são os clientes que mais gastaram em serviços?
- Qual o funcionário que mais realizou serviços?
- Quais peças foram mais utilizadas?
- Qual o faturamento total da oficina no mês?
- Quais veículos tiveram mais ordens de serviço?
- Quais fornecedores fornecem peças para determinado tipo de serviço?

---

## 📂 Estrutura do Repositório

```
📁 banco_oficina/
├── 📄 script_criacao.sql         # Criação e inserção de dados
├── 📄 consultas.sql              # Consultas SQL complexas
└── 📄 README.md                  # Este arquivo
```

---

## 🤖 Observações
Este projeto pode ser usado como base para construção de aplicações completas de gestão de oficinas, integrando com front-end ou APIs. Fique à vontade para clonar, adaptar e evoluir!

---

👨‍💻 Projeto realizado para fins didáticos – por Guilherme Felipe Cosmos
