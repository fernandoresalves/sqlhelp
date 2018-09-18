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


### Explorando Synonyms

```sql
SELECT NAME, BASE_OBJECT_NAME 
FROM SYS.SYNONYMS 
ORDER BY NAME
```

REF.:https://docs.microsoft.com/en-us/sql/relational-databases/system-catalog-views/sys-synonyms-transact-sq
