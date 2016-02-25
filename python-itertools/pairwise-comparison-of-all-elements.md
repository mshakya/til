# To create a pair of all elements in an interatble

This can be done using `combination` function of the package `itertools`.

```python 
from itertools import combination
combinations(iterable, 2)
```

This will generate an iteratble with all possible paired (`2`) combination of all the element in the iterable (list, tuple, etc.)