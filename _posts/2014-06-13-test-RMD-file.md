---
layout: post
title: Test R Markdown Post
description: "First R Markdown Post"
modified: 2014-06-13
tags: [R]
comments: true
image:
  feature: texture-feature-05.jpg
  credit: Texture Lovers
  creditlink: http://texturelovers.com
---



Testing R Markdown Docs with Jekyll
========================================================

This is an R Markdown document. Markdown is a simple formatting syntax for authoring web pages (click the **Help** toolbar button for more details on using R Markdown).

When you click the **Knit HTML** button a web page will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
summary(civic_raw)
```

```
##  Odometer..mi.   Trip.Distance                Date      Fill.Amount   
##  Min.   :12424   Min.   : 98   7/12/2013        :  2   Min.   : 3.12  
##  1st Qu.:25735   1st Qu.:356   8/23/2011        :  2   1st Qu.:10.97  
##  Median :38673   Median :378   1/1/2013         :  1   Median :11.24  
##  Mean   :38311   Mean   :379   1/10/2014 8:17:00:  1   Mean   :11.08  
##  3rd Qu.:50944   3rd Qu.:406   1/11/2012        :  1   3rd Qu.:11.47  
##  Max.   :63182   Max.   :455   1/12/2013        :  1   Max.   :12.85  
##                                (Other)          :127                  
##  Fill.Units Price.per.Unit  Total.Price        MPG      
##  Gal:135    Min.   :2.62   Min.   :11.6   Min.   :28.6  
##             1st Qu.:3.42   1st Qu.:38.1   1st Qu.:31.8  
##             Median :3.60   Median :39.7   Median :34.0  
##             Mean   :3.60   Mean   :39.9   Mean   :34.2  
##             3rd Qu.:3.75   3rd Qu.:42.3   3rd Qu.:36.7  
##             Max.   :4.13   Max.   :48.0   Max.   :43.9  
##                                                         
##                   Note                  Location   Categories
##                     :134                    :111       :  2  
##  Safeway rewards -$1:  1   AmeriGo          :  1   Fuel:133  
##                            Exxon Edsall Rd  :  1             
##                            Exxon Lee Highway:  5             
##                            Sunoco Rosslyn   : 17             
##                                                              
##                                                              
##     Latitude      Longitude           ID       
##  Min.   :38.3   Min.   :-78.0   Min.   :  2.0  
##  1st Qu.:38.9   1st Qu.:-77.1   1st Qu.: 35.5  
##  Median :38.9   Median :-77.1   Median : 69.0  
##  Mean   :39.5   Mean   :-76.8   Mean   : 69.1  
##  3rd Qu.:38.9   3rd Qu.:-77.1   3rd Qu.:102.5  
##  Max.   :43.2   Max.   :-71.4   Max.   :137.0  
##  NA's   :102    NA's   :102
```

You can also embed plots, for example:

![plot of chunk QQ Plot](images/QQ Plot.png) 

And here's another plot:

![plot of chunk distance vs MPG](images/distance vs MPG.png) 

