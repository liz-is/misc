# test lazy load
Liz Ing-Simmons  
29 July 2014  
cache.lazy = TRUE

```r
Sys.time()
```

```
## [1] "2014-07-29 18:43:10 BST"
```

cache.lazy = FALSE

```r
Sys.time()
```

```
## [1] "2014-07-29 18:46:48 BST"
```


```r
sessionInfo()
```

```
## R version 3.1.0 (2014-04-10)
## Platform: x86_64-apple-darwin10.8.0 (64-bit)
## 
## locale:
## [1] en_GB.UTF-8/en_GB.UTF-8/en_GB.UTF-8/C/en_GB.UTF-8/en_GB.UTF-8
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## loaded via a namespace (and not attached):
##  [1] codetools_0.2-8  digest_0.6.4     evaluate_0.5.5   formatR_0.10    
##  [5] htmltools_0.2.4  knitr_1.6        rmarkdown_0.2.52 stringr_0.6.2   
##  [9] tools_3.1.0      yaml_2.1.13
```
