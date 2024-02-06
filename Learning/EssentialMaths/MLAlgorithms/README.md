
# Habbits

1. Import the data
2. Explore the data
3. filter the data

Regression:
1.  It's always a good idea to begin any regression analysis by examining the correlation matrix of your data.


```
 df.select_dtypes(include=['float64']).corr()
```
