### - Initialize an empty dataframe with column names
```
perChromCis <- data.frame(matrix(ncol = 3, nrow = 0))
colnames(perChromCis) <- c('sample', 'cis','region')
```
```
> str(perChromCis)
'data.frame':   0 obs. of  3 variables:
 $ sample: logi 
 $ cis   : logi 
 $ region: logi 
```
