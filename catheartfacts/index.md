---
title       : Cat Heart Facts
subtitle    : 
author      : Chris Hawkins
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Overview

### Pet owners now have a neat way to find out more information about their cats. Introducing...

### <center> <h3>🐱 ❤ ⚖ </h3> <h4>(Cat, Heart, Scale) </h4></center>

---


```r
library(MASS)
model <- glm(Hwt ~ Bwt, data = cats)
plot(cats$Hwt ~ cats$Bwt)
abline(model)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

Cat heart weight is predicted by using a linear model based on a regression of the _cats_ dataset included with the R MASS package.

---

## In Action

### You can see the application here:
### [https://chrishawkins.shinyapps.io/catheartfacts] (https://chrishawkins.shinyapps.io/catheartfacts)

---

## Thanks

### Thanks for bearing with me through the ridiculousness.

*Chris Hawkins*
[chrishawkins.com.au] (http://chrishawkins.com.au)