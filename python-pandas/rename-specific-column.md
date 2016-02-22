#Rename specific column in pandas df

- for single column
```python
df.rename(columns={'old_name': 'new_name'}, inplace=True)
```
- for multiple columns
```python
df.rename(columns={'old_name1': 'new_name1'}, inplace=True)
```
