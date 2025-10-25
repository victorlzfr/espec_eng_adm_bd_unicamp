## Achievement
Implementação prática de banco de dados no SQL Server com criação de estrutura completa, aplicando conceitos de DDL, constraints, índices e modelagem relacional aprendidos na sessão da tarde.

## Date: 2025-10-25
## Time Spent: 1 hour 46 minutes

## Process Completed

1. **Arquitetura SQL Server**
   - SQL Server Management Studio (SSMS) e interface gráfica
   - System databases: master, model, tempdb, msdb
   - Estrutura de armazenamento: arquivos .mdf, .ndf, .ldf
   - Tabelas do sistema e stored procedures administrativas

2. **Transact-SQL (T-SQL) - DDL**
   - Tipos de dados do SQL Server (char, varchar, int, money, datetime, etc.)
   - Comandos CREATE, ALTER, DROP para bancos e tabelas
   - Restrições de integridade: PRIMARY KEY, FOREIGN KEY, UNIQUE
   - Definição de colunas NULL/NOT NULL e valores DEFAULT

3. **Implementação Prática**
   - Criação do banco de dados "espbd" com arquivos físicos
   - Definição completa do schema com 5 tabelas relacionadas
   - Aplicação de chaves primárias, estrangeiras e constraints UNIQUE
   - Criação estratégica de índices para otimização de performance
   - Script de remoção preparado para todo o ambiente

4. **Modelagem Relacional Aplicada**
   - Tabelas: cliente, vendedor, produto, pedido, item_do_pedido
   - Relacionamentos: cliente-pedido, vendedor-pedido, produto-item_pedido
   - Chave primária composta em item_do_pedido
   - Índices em colunas frequentemente usadas em consultas
