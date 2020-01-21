---
layout: single
title: "Reproducible research"
author: "Fabio CRUZ"
permalink: "/PPT-2/"
output:
  html_document:
    keep_md: true
  revealjs::revealjs_presentation:
    theme: white
#    highlight: pygments
    center: true
    transition: none
#    self_contained: true
    reveal_options:
      navigationMode: linear
      width: 1600
      height: 900
      slideNumber: true
      previewLinks: true
      progress: true

---




#  how do you develop the analysis so that you can communicate to someone what was done?


```r
library(fivethirtyeight)
library(tidyverse)
```


The dataset contains information on 1794 movies released between 1970 and 2013. However we'll focus our analysis on movies released between 1990 and 2013.


```r
bechdel90_13 <- bechdel %>% 
  filter(between(year, 1990, 2013))
```




## Excel..

[excel choas](Figures/intro/excel-chaos.jpg)

## Excel..

[excel choas](Figures/intro/excel-chaos.jpg)

Sometimes (more often than less) is a mess if they want to reproduce the work?


# Main concepts

## 


## why is it
- Turn off alarm
- Get out of bed

## Why do we need?

- Analytic data
- Analytic code
- Documentation (data and code)
- Standard means of distribution





