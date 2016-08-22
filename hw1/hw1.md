# Homework 1
![](hw1_header.png)
  
![](hw1_q1.1.png)
  
![](hw1_a1.1.png)

```r
# verifying in R
a = matrix(c(3,2,6,5), 2, 2)
b = matrix(c(3, 2), 2, 1)
solve(a, b)
```

```
##      [,1]
## [1,]    1
## [2,]    0
```
  
![](hw1_q1.2.png)
  
![](hw1_a1.2.png)

```r
# verifying in R
a = matrix(c(1,2,-2,3), 2, 2)
b = matrix(c(1, 2), 2, 1)
solve(a, b)
```

```
##      [,1]
## [1,]    1
## [2,]    0
```
  
![](hw1_q2.1.png)

```r
# solving in R
a = matrix(c(1, 1, 1, -1, 0, -1, 0, 1, -2), 3, 3)
b = matrix(c(3, 6, 0), 3, 1)
solve(a, b)
```

```
##      [,1]
## [1,]  4.5
## [2,]  1.5
## [3,]  1.5
```
  
![](hw1_q2.2.png)

```r
# solving in R
a = matrix(c(1,2, 4, 1, 1, 3, 1, 0, 3), 3, 3)
b = matrix(c(1, 3, 4), 3, 1)
solve(a, b)
```

```
##      [,1]
## [1,]    1
## [2,]    1
## [3,]   -1
```
  
![](hw1_q3.png)
  
![](hw1_a3.1.png)
![](hw1_a3.2.png)

```r
# solving in R
a = matrix(c(1, .45, -.25, .14, 1, -.55, .75, .20, 1, 0, -.25, .2, 1, 0, -.25, .1), 4, 4)
b = matrix(c(250, 0, 0, 37.5), 4, 1)
solve(a, b)
```

```
##          [,1]
## [1,] 76.38889
## [2,] 62.50000
## [3,] 31.94444
## [4,] 79.16667
```
  
![](hw1_q4.png)
  
![](hw1_a4.png)
  
![](hw1_q5.png)
  
![](hw1_a5.png)