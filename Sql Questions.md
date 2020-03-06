1. Triggers
```
CREATE TRIGGER [schema_name.]trigger_name
ON table_name
AFTER  {[INSERT],[UPDATE],[DELETE]}
[NOT FOR REPLICATION]
AS
{sql_statements}
```
Triggers can be used for auditing purposes (Recording Inserts, Updates, Delete on a table), to enforce business rules and derive column values.\
Queries do not change the contents of the database, so they cannot fire a TRIGGER without an event.

Learn more about different trigger types from [here](https://www.sqlservertutorial.net/sql-server-triggers/)\
Informative article on triggers and their usability 
[[1]](https://www.databasejournal.com/features/mysql/the-wonderful-and-not-so-wonderful-things-about-mysql-triggers.html)
[[2]](https://www.red-gate.com/simple-talk/sql/t-sql-programming/triggers-threat-menace/)

2. Views vs x