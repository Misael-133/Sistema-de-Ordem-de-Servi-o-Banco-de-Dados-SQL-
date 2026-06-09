# Sistema de Ordem de Serviço (SQL)

Projeto acadêmico de banco de dados relacional para gerenciamento de ordens de serviço de uma empresa de manutenção de equipamentos.

## 📌 Objetivo

Modelar e implementar um banco de dados capaz de controlar:

- clientes
- técnicos
- serviços
- ordens de serviço
- finalizações
- relação entre ordens e serviços executados

O projeto simula um cenário real de assistência técnica, com cadastro de dados, relacionamento entre tabelas e consultas SQL para análise das informações.

## 🛠️ Tecnologias utilizadas

- MySQL
- SQL
- MySQL Workbench

## 🧱 Estrutura do banco

O banco foi modelado com as seguintes tabelas principais:

- `Tecnico`
- `Cliente`
- `Servico`
- `Finalizacao`
- `OrdemServico`
- `OrdemServico_Servico`

A modelagem inclui chaves primárias, chaves estrangeiras e relacionamento entre entidades, incluindo uma tabela associativa para representar os serviços vinculados a cada ordem de serviço. :contentReference[oaicite:0]{index=0}

## 📊 Funcionalidades implementadas

- criação do banco de dados
- criação das tabelas
- definição de relacionamentos
- inserção de dados para simulação
- consultas SQL com filtros
- consultas com `JOIN`
- consultas com `GROUP BY`
- somatórios com `SUM`
- ordenação de resultados com `ORDER BY`

## 🔎 Exemplos de consultas realizadas

O projeto inclui consultas como:

- total de serviços cadastrados
- ordens de serviço em aberto
- listagem dos serviços vinculados a cada ordem
- cálculo do valor total por ordem de serviço 

## 💡 Aprendizados demonstrados

Neste projeto foram praticados conceitos importantes de banco de dados, como:

- modelagem relacional
- integridade referencial
- normalização básica
- uso de chaves primárias e estrangeiras
- consultas SQL intermediárias
- organização de dados em cenário realista

## ▶️ Como executar

1. Abra o MySQL Workbench
2. Execute o script SQL do projeto
3. O banco `Empresa` será criado
4. As tabelas e os registros serão inseridos automaticamente
5. Execute as consultas no final do script para visualizar os resultados

