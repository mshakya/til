# Subsetting a column based on results of a query

```sql
SELECT * FROM YourTable 
WHERE `YourTable`.`notes` IN 
(SELECT `ColleageueTable`.`notes` FROM `ColleageueTable` WHERE `ColleageueTable.NoteTitle` = 'about me');
```