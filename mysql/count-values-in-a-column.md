# Count values in a column

``` sql
SELECT `column_tobe_counted`, COUNT(*) FROM `table_with_column` GROUP BY `column_tobe_counted`;
```

If `column_tobe_counted` contains last name, then this one liner will count the number each last name in `table_with_column`. 
Resultant table contains one column of last name, and another of its count.