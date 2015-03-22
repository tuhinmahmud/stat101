---
title       : Statistics-101  
subtitle    : using R
author      : Tuhin Mahmud
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Power 
https://tuhinmahmaud.shinyapps.io/PowerApp/



--- .class #id 

## Central limit Theorem
https://tuhinmahmaud.shinyapps.io/CentralLimitApp/

---  Spearman's p and Pearson's r

```r
X <- data.frame("attributes"=NA,"Pearson'r"=NA,"Spearman's r"=NA)
X[1][1]<-"trend"
X[1][2]<-"linear" 
```

```
## Warning in `[<-.data.frame`(`*tmp*`, 1, value = structure(list(attributes
## = "trend", : provided 2 variables to replace 1 variables
```

```r
X[1][3]<-"monotonic"
```

```
## Error in `[<-.data.frame`(`*tmp*`, 3, value = "monotonic"): new columns would leave holes after existing columns
```

```r
X[2][1]<-"sampling distribution"
X[2][2]<-"normal"
```

```
## Warning in `[<-.data.frame`(`*tmp*`, 2, value = structure(list(Pearson.r =
## "sampling distribution", : provided 2 variables to replace 1 variables
```

```r
X[2][3]<-"non normal"
```

```
## Error in `[<-.data.frame`(`*tmp*`, 3, value = "non normal"): new columns would leave holes after existing columns
```

```r
X[3][1]<-"data"
X[3][2]<-"interval"
```

```
## Warning in `[<-.data.frame`(`*tmp*`, 3, value =
## structure(list(Spearman.s.r = "data", : provided 2 variables to replace 1
## variables
```

```r
X[3][3]<-"non parametric"
```

```
## Error in `[<-.data.frame`(`*tmp*`, 3, value = "non parametric"): new columns would leave holes after existing columns
```

```r
library(panda)
```

```
## Error in library(panda): there is no package called 'panda'
```

```r
pander(X[1:3,1:3])
```


------------------------------------------------------------
  &nbsp;    attributes        Pearson.r        Spearman.s.r 
---------- ------------ --------------------- --------------
  **1**       trend     sampling distribution      data     

  **NA**        NA               NA                 NA      

 **NA.1**       NA               NA                 NA      
------------------------------------------------------------

--- t-test


