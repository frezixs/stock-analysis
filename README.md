# stock-analysis
## Overview of the Project 
### The Purpose 
    Help steve figure out which stock he should choose by analyzing the trend of 12 stocks in 2017 and 2018 
### The Background 
    Given information of 12 stocks in 2017 and 2018, with dates. volumes and closing prices 

## Results 
![VBA_Challenge_2017](https://user-images.githubusercontent.com/49871539/117592556-fe578200-b106-11eb-8e87-9292ca84ca20.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/49871539/117592557-fe578200-b106-11eb-88f7-630aafe878ce.png)
In 2017 most stocks are increasing besides TERP, but the decrease is acceptable 
DQ,ENPH, FSLR,SEDG has significantly good return 
In 2018 most stocks are decreasing besides ENPH and RUN. 
Maybe we Steve should buy ENPH because this stock performs well in 2017 and 2018 

For the run time, in module 2 practice it is about 0.8s, after refactering it my run time decrease to about 0.1s 

## Summary 
### In general 
#### Advantange 
Refactoring code can save run time and avoid bugs 
#### Disadvantage
Refactoring may use some difficult functions or complex logics which makes the code harder to understand. 

### In this assignment 
#### Advantage 
Significantly decrease the run time, the reason is that in our original code, we have a nested loop, so we go over these 
3012 rows of stock data 12 times, after refactoring, we mananged to avoid using this nested loop, so we just go over these 3012 rows of stock data once. 
#### disadvantage 
If there is no instruction, it is hard to come up with this idea, in fact, I think the nested loop method is easier to understand. 
Also, since we need to make everything into arrays, we may have more chances to have bugs. For fresh VBA users, as I do, I think the nested loop method is safer. 

