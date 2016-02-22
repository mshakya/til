# Count values in a column

``` sql
SELECT `column_tobe_counted`, COUNT(*) FROM `table_with_column` GROUP BY `column_tobe_counted`;
```

If `column_tobe_counted` contains last name, then this one liner will count the number of times each last name appear in `table_with_column`. 
Resultant table contains one column of last name, and another of its count.