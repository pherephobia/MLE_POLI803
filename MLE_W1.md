---
title: "MAXIMUM LIKELIHOOD ESTIMATION for FALL-2019"
shorttitle: Led by Dr. Bird
author: Sanghoon Park (Univ. of South Carolina)
date: Aug. 28, 2019
---



```{r setup, include=FALSE}
## 이 Rmd 파일에서 사용할 Rdata가 있는 디렉토리 설정
## echo = TRUE는 모든 Code-chunk의 코드들을 Output에 
## '보이도록' 출력하라는 디폴트 명령.
library(knitr)
library(tidyr)
library(ggplot2)
library(kableExtra)
opts_knit$set(c(root.dir = 
                  "C:/Users/예제 데이터 디렉토리"),
              (echo = TRUE))
## 예를 들어, 위의 opts_knit 설정을 하시고 나면 데이터를 부를 때,
## 디렉토리 일체를 쓸 필요가 없이
# data <- read.csv("data.csv")
## 위와 같은 식으로 로드하면 됩니다. "" 그 디렉토리 안에 해당 csv
## 파일이 있다는 가정하에요.
```


## R 마크다운

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
