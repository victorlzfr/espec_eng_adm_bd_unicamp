## Conquista
Estudo completo dos fundamentos de T-SQL DML (Data Manipulation Language) incluindo operações de manipulação de dados, consultas avançadas e gerenciamento de transações.

## Data: 2025-11-02
## Tempo Gasto: 39 minutos

## Processo Concluído

1. **Operações Básicas DML**
   - Comando INSERT para inserção de dados (com e sem especificação de colunas)
   - Comando UPDATE para atualização de dados (linhas específicas e todas as linhas)
   - Comando DELETE para exclusão de dados (com condições e TRUNCATE TABLE)
   - Inserção de dados a partir de resultados de SELECT

2. **Consultas e Seleção de Dados**
   - Comando SELECT com cláusulas WHERE, GROUP BY, HAVING, ORDER BY
   - Operadores relacionais, lógicos e aritméticos em consultas
   - Funções de agregação (COUNT, MAX, MIN, SUM, AVG)
   - Eliminação de duplicatas com DISTINCT
   - Tratamento de valores nulos (IS NULL, IS NOT NULL)

3. **Junções e Subconsultas**
   - INNER JOIN para relacionamento entre tabelas
   - OUTER JOIN (LEFT, RIGHT, FULL) para inclusão de todos os registros
   - CROSS JOIN para produto cartesiano
   - Subconsultas (subqueries) aninhadas com operadores IN e =

4. **Gerenciamento de Transações**
   - Conceitos de transações e propriedades ACID
   - Estados de transação (Ativo, Parcialmente Efetivado, Efetivado, Falha, Encerrado)
   - Comandos BEGIN TRANSACTION, COMMIT, ROLLBACK, SAVE TRANSACTION
   - Mecanismos de lock (bloqueio) e granularidade
   - Modos de transação no SQL Server (Autocommit, Explicit, Implicit)
   - Exemplos práticos de transações para cadastro e transferências

5. **Esquemas de Banco de Dados**
   - Análise de esquema físico exemplo com tabelas cliente, vendedor, pedido, produto
   - Estudo do esquema lógico do banco PUBS (exemplo Microsoft)
   - Implementação de chaves primárias e estrangeiras
