# Replace or fill values in a column based on value from another column

``` python
import numpy as np

df['column_to_replace_or_fill'] = np.where(df['column__based_on'] == 'value_to_check', 'value_to_fill_if_condition_True', 'value_to_fill_if_false')
```

