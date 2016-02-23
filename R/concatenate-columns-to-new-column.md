# concatenating values of two or multiple columns into one

```{R}
df$new_column <- paste(df$concatenate_column1, df$concatenate_column2, sep="_")
```
this will result in a `df$new_column` with value like `string1_string2`.