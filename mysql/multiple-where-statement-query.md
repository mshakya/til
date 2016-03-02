# Use multiple `WHERE` statement in a query

##Example with `AND`
``` sql
SELECT * FROM fav_table WHERE fav_table.fav_column = 'present' AND fav_table.unfav_column = 'not';
```

##Example with `OR`
``` sql
SELECT * FROM fav_table WHERE fav_table.fav_column = 'present' OR fav_table.just_column = 'present';
```

## Example with `AND` and `OR`
``` sql
SELECT * FROM fav_table WHERE fav_table.fav_column = 'present' AND (fav_table.unfav_column = 'present' OR fav_table.unfav_column = 'not';
```
