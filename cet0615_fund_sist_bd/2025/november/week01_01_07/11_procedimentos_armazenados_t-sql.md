## Achievement
Estudo completo de procedimentos armazenados (stored procedures) em T-SQL com transações e aninhamento

## Date: 2025-11-04
## Time Spent: 20 minutes

## Process Completed

1. **Conceitos Fundamentais de Stored Procedures**
   - Definição de procedures como conjuntos de comandos SQL compilados
   - Vantagens: encapsulamento, redução de erros, segurança e performance
   - Estrutura básica do comando CREATE PROCEDURE

2. **Parâmetros e Execução**
   - Parâmetros por valor e por referência (com OUTPUT)
   - Valores default para parâmetros
   - Formas de execução: posicional e nomeada
   - Comando RETURN para valores inteiros de retorno

3. **Transações em Procedures**
   - Implementação de transações atômicas dentro de procedures
   - Procedure ins_pessoa_fisica: cadastro completo cliente + pfisica
   - Procedure ins_conta: criação e vinculação de contas
   - Verificações com @@ROWCOUNT para controle de sucesso/falha

4. **Aninhamento de Procedures**
   - Procedure trans_completa: exemplo de chamada aninhada
   - Reutilização de procedures menores em transações complexas
   - Gerenciamento de retornos entre procedures aninhadas
   - Importante: @@ROWCOUNT é zerado por comandos IF, PRINT

5. **Gerenciamento de Procedures**
   - Comando ALTER PROCEDURE para modificações
   - sp_rename para alterar nomes mantendo permissões
   - DROP PROCEDURE para exclusão
