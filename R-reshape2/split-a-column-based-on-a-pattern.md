#Split column based on a pattern

```{R}
# load the library
library(reshape2)

df <- data.frame(rollcall=1:3, NAME=c('John_Smith', 'Megan_Darwin', 'Jessica_Wallace'))
df = transform(df, NAME = colsplit(NAME, pattern = "_", names = c('FIRST', 'LAST')))
```