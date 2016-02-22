# Replace value in a column 1 with corresponding value from another column 2

``` {r}
df$column_to_replace_value <- ifelse(df$column_to_replace_value == "", df$column_to_replace_value_FROM, df$column_to_replace_value)
```

this script replaces empty `""` values in `column_to_replace_value` with corresponding values from `column_to_replace_value_FROM`. Check the data type of the columns to make sure if values being replaced are `character` type.