# sqlhelp
Comandos úteis do Sql

## SQL Server

### Característica das colunas de uma tabela.
```sql
SELECT *
FROM INFORMATION_SCHEMA.COLUMNS
WHERE 
     TABLE_NAME = 'yourTableName' AND 
     COLUMN_NAME = 'yourColumnName'
```
     
REF.: https://docs.microsoft.com/pt-br/sql/relational-databases/system-information-schema-views/columns-transact-sql
