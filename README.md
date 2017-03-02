Hello Octocat
-------------

I love octocat. She's the coolest cat in town
![](https://dl.dropboxusercontent.com/u/11805474/painblogr/biostats/assignments/octocat.png)

quick\_look

    data(anscombe)
    dim.data.frame(anscombe)

    ## [1] 11  8

    colnames(anscombe)

    ## [1] "x1" "x2" "x3" "x4" "y1" "y2" "y3" "y4"

    head(anscombe)

    ##   x1 x2 x3 x4   y1   y2    y3   y4
    ## 1 10 10 10  8 8.04 9.14  7.46 6.58
    ## 2  8  8  8  8 6.95 8.14  6.77 5.76
    ## 3 13 13 13  8 7.58 8.74 12.74 7.71
    ## 4  9  9  9  8 8.81 8.77  7.11 8.84
    ## 5 11 11 11  8 8.33 9.26  7.81 8.47
    ## 6 14 14 14  8 9.96 8.10  8.84 7.04

    tail(anscombe)

    ##    x1 x2 x3 x4    y1   y2   y3    y4
    ## 6  14 14 14  8  9.96 8.10 8.84  7.04
    ## 7   6  6  6  8  7.24 6.13 6.08  5.25
    ## 8   4  4  4 19  4.26 3.10 5.39 12.50
    ## 9  12 12 12  8 10.84 9.13 8.15  5.56
    ## 10  7  7  7  8  4.82 7.26 6.42  7.91
    ## 11  5  5  5  8  5.68 4.74 5.73  6.89

    summary(col(anscombe))

    ##        V1          V2          V3          V4          V5          V6   
    ##  Min.   :1   Min.   :2   Min.   :3   Min.   :4   Min.   :5   Min.   :6  
    ##  1st Qu.:1   1st Qu.:2   1st Qu.:3   1st Qu.:4   1st Qu.:5   1st Qu.:6  
    ##  Median :1   Median :2   Median :3   Median :4   Median :5   Median :6  
    ##  Mean   :1   Mean   :2   Mean   :3   Mean   :4   Mean   :5   Mean   :6  
    ##  3rd Qu.:1   3rd Qu.:2   3rd Qu.:3   3rd Qu.:4   3rd Qu.:5   3rd Qu.:6  
    ##  Max.   :1   Max.   :2   Max.   :3   Max.   :4   Max.   :5   Max.   :6  
    ##        V7          V8   
    ##  Min.   :7   Min.   :8  
    ##  1st Qu.:7   1st Qu.:8  
    ##  Median :7   Median :8  
    ##  Mean   :7   Mean   :8  
    ##  3rd Qu.:7   3rd Qu.:8  
    ##  Max.   :7   Max.   :8
