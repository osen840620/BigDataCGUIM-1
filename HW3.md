Untitled
================

各隊最辛苦的球員
----------------

計算依據為出戰分鐘數最多的球員

``` r
MaxPoint<-aggregate(TotalPoints~Team,NBA1415,max)
NBA1415MaxPoint<-merge(NBA1415,MaxPoint)
NBA1415MaxPoint[order(NBA1415MaxPoint$TotalPoints,decreasing = T),c("Team","Name","TotalPoints")]
```

<<<<<<< HEAD
    ##    Team             Name TotalPoints
    ## 11  HOU     James Harden        2217
    ## 10  GSW    Stephen Curry        1900
    ## 21  OKL Russel Westbrook        1886
    ## 6   CLE     Lebron James        1740
    ## 25  POR   Damian Lillard        1720
    ## 19  NOR    Anthony Davis        1656
    ## 13  LAC       Chris Paul        1564
    ## 7   DAL      Monta Ellis        1513
    ## 29  UTA   Gordon Hayward        1463
    ## 5   CHI        Pau Gasol        1446
    ## 26  SAC         Rudy Gay        1432
    ## 22  ORL   Nikola Vucevic        1428
    ## 15  MEM       Marc Gasol        1413
    ## 18  MIN   Andrew Wiggins        1387
    ## 30  WAS        John Wall        1385
    ## 24  PHO     Eric Bledsoe        1377
    ## 16  MIA      Dwyane Wade        1331
    ## 28  TOR       Kyle Lowry        1244
    ## 3   BRO      Brook Lopez        1236
    ## 1   ATL     Paul Millsap        1218
    ## 8   DEN        Ty Lawson        1143
    ## 9   DET   Andre Drummond        1130
    ## 2   BOS    Isaiah Thomas        1101
    ## 4   CHA     Al Jefferson        1080
    ## 27  SAN       Tim Duncan        1070
    ## 17  MIL  Khris Middleton        1055
    ## 20  NYK  Carmelo Anthony         966
    ## 12  IND       C.j. Miles         942
    ## 23  PHI Robert Covington         927
    ## 14  LAL      Jordan Hill         841

各隊得分王
----------

計算依據為全季總得分最多的球員
=======
    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

![](HW3_files/figure-markdown_github/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
>>>>>>> origin/master