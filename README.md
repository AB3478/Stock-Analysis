# Stock-Analysis

## Overview of Project

#### Steve is interested in using Visual Basic Applications (VBA) to automate the process of evaluating stock data. To facilitate Steve’s data analysis, we’ll refactor the code to ensure the VBA script is as fast, efficient, and user-friendly as possible. 

## Results

#### To determine how stocks performed between 2017 and 2018, we identified the stock, total daily volume, and the return (or the difference between the ending price and the starting price). Stocks had significantly greater returns in 2017—all but one of the stocks had positive returns in 2017. The majority of stocks in the 2018 ticker search had largely negative returns. Of the 12 stocks, only 2 had positive returns (ENPH, RUN). Below or the returns for both 2017 and 2018:

![](https://github.com/AB3478/Stock-Analysis/blob/main/Resources/Stock%20Analysis%20Results%202017.png)

![](https://github.com/AB3478/Stock-Analysis/blob/main/Resources/Stock%20Analysis%20Results.png%202018.png)

#### The execution time for 2017 was approximately 2 seconds; the execution time for 2018 was approximately 2.5 seconds. Refactoring the code reduced the run times for both 2017 and 2018, see below:

![](https://github.com/AB3478/Stock-Analysis/blob/main/Resources/Stock%20Analysis%202017.png)

![](https://github.com/AB3478/Stock-Analysis/blob/main/Resources/Stock%20Analysis%202018.png)

## Summary

### What are the advantages or disadvantages of refactoring code? 

-	Refactoring code helps not only the person reading the results, but also the programmer. Steve can now use the readable code as well as a run button to conduct his data analysis more efficiently and easily share the results. Refactoring also helps reduce the run time of macros; if Steve is interested in larger data sets, refactoring can help macros run more efficiently.

-	Refactoring is time consuming, and in our case, only saved a couple of seconds. For smaller data sets, it may not be cost-efficient. If not done correctly, refactoring can also introduce bugs.

### How do these pros and cons apply to refactoring the original VBA script?

- Refactoring the VBA script made the code easier to understand and helped execute the macros faster. However, the data set was small enough that refactoring did not make a meaningful difference in overall run time.
