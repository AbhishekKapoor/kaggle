---
title       : Kaggle Mobile Ad Competition
subtitle    : Presentation for Analysis
author      : Abhishek Kapoor
job         : Mobile Ad Competition
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Back ground

1. Hi Friend, we take this competition as an opportunity to learn R and to build an   architecture around R and big data
2. We are using Slidify and  R Markdown for reporting
3. This competition is hosted on Kaggle - (http://www.kaggle.com/c/avazu-ctr-prediction)
  


--- .class #id 

## Installation

R - packages requirement 
ffbase,ff,ffbase2,lubridate,tidyr



```r
rm(list=ls())
if(require(Revobase)){
  setMKLthreads(4)
}
```

```
## 
## Number of threads at maximum: no change has been made.
```

```r
setwd("C:/Users/Abhishek Kapoor/Documents/GitHub/kaggle/Ad Click predictation/data")
#install.packages ("ff",dep=T)  ###if not installed in ur system

##install.packages ("ffbase",dep=T)
#install.packages("devtools")
#devtools::install_github("edwindj/ffbase2")
```
