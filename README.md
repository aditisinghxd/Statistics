 # Non-Parametric tests:

### •	Unlike parametric tests we do not assume that data is normal
### •	Non-Parametric tests are used when data is strongly non-normal (normality can be tested using normality test where p-value < 0.05 then the data is not normal)
### •	Also used when sample size is too small 

# ________________________________________

## Assumptions: 
### 1.	Observations in the sample are independent and derived from the same population.
### 2.	 For two sample designs, they are of equal shape and spread.

# ________________________________________

## Limitations:
### 1.	They are less powerful than the corresponding parametric test when the data is normal because for normal data, they are less likely to reject the null hypothesis when it is false.
### 2.	We are often required to modify the hypothesis because in non-parametric tests we test the median therefore we get different result for non-symmetric population.

# ________________________________________

## Types of non-parametric tests:





                                                Non-Parametric Tests
                                                         |
                               __________________________________________________
                              |                          |                       |
                     To compare median           Test to compute             Others
                                           (used to compute average,    
                                            differences and slopes)



## To compare median:

## One Sample	
  ###   > Estimates population median and compares the result to a reference/ target value  
  ###  > 1.	One sample sign test:  used when the distribution is symmetric
  ###    2.	One sample Wilcoxon test:  used when the distribution is non symmetric

## Two sample	
###     > In this test we determine whether the median of two groups are different
###     > 1.	Mann Whitney test
      
## Paired Sample	
###     > Used to determine whether the population medians of 2 groups differ when the data is in pair
###     > We first calculate the difference between the population and then use the one sample Wilcoxon test
     
## 2 or more sample
###     > Compares medians of two or more populations whose distribution have same shape and equal variance
###     > 1.	Kruskal Wallis test
###       2.	Mood’s median test
###       3.	Friedman test 
       
       

##Tests to compute:

## Pairwise Averages	
###     > used to calculate and store the means of each possible pair of values in the data set
    
### Pairwise Slopes 
###     > slopes between two columns where each row represents a coordinate point in x-y plane
     
## Pairwise Differences
###     > Used to calculate and store differences between each possible pair of values in the data set




## Others:
###      > Runs Test: To determine whether the order of data is random
