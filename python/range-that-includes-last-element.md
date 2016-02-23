# function for generating range that also includes last element.

When generating range in python2.7, it doesnt include the last element. So, here is a hack that does.

``` python
range1 = lambda start, end: range(start, end+1)
```