# Green Stock analysis

## Overview of Project: Explain the purpose of this analysis.

The purpose of this analysis is the helps Steve to show his parents the performance of the green industry between 2017 and 2018. The analysis will show if it is interesting to invest in DAQO New energy Corp or if they are other companies that have performed better.
This analysis will help Steve’s parents to take a better decision based on our founding’s.

## Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

At a glance, we can see that the green energy industry stocks were more performant in 2017 compared to 2018.
In 2017 the entire market performed well except Terp (-7.2%), DAQO lead the market in term of return on investment of almost + 200% (2199.4%), but DAQO Stock hasn’t been traded that much compared to the other stock. In fact, DAQO has the lowest volume of transactions that year.
So, the investors that have identified DAQO in the market in 2017 were very happy of their investment.
In 2018 the market has plunged except ENPH and RUN. DAQO have the record of loss for - 62.6%. This could be due the low volume of transaction which can amplify the performance of the stock when it rose or decline.
Now Steve’s parents have all the information to invest in the rights stock. ENPH and RUN are more stable in term of performance over 2017 and 2018. We can recommend those stocks.

#### All Stock Analysis Refactored 2017![All stocks Analysis  2017](https://user-images.githubusercontent.com/89410157/131737443-a072a05e-9b94-43e4-8b87-ddadfedf6123.png)

#### All Stock Analysis Refactored 2018![All stocks Analysis  2018](https://user-images.githubusercontent.com/89410157/131737487-ceeaa938-14fd-41db-89d8-fd68e84488cb.png)

To perform this analysis by using VBA, the analysis was done during the module, so the main task was to edit of refactor to code and provide the same result.
The first objective is accomplished as we have the same result for the original and the refactored analysis.
The analysis original analysis and the refactored Analysis are run in 0.5429688 for 2017 and 0.5351563 for 2018. The timings are similar so we can say that refactoring hasn’t affect the performance of the code that much.

##### Original Timer 2017![Original Timer 2017](https://user-images.githubusercontent.com/89410157/131738086-97b8aa61-f0ca-41dd-9e7b-4bd149ea1462.png)

##### Refactored Timer 2017![Timer 2017](https://user-images.githubusercontent.com/89410157/131738482-8191232e-bf65-40f6-8a3d-704e94becd56.png)

##### Original Timer 2018![Original Timer 2018](https://user-images.githubusercontent.com/89410157/131738523-360b3a72-7d0a-44df-8dfe-408e79d289f1.png)

##### Refactored Timer 2018![Timer  2018](https://user-images.githubusercontent.com/89410157/131738555-2915c0ca-2822-4768-a733-d413ccd85994.png)

## Summary: In a summary statement, address the following questions.

### What are the advantages or disadvantages of refactoring code?

The advantages of the refactoring code are multiple, first helps to understand the code before working on it which is very Importing in coding. Also, the refactoring helps to gain time because we will have the base code that we have to update. In coding is important to do not repeat or selves and use the existing code we have already or someone founding. Refactoring helps on that process.
The main disadvantage is linked to the fact that the update can lead to bug, and it can take time to identify and correct them. Also, by refactoring a code we must keep in mind that if we update a variable, we will have to track them and update then in all the code they are used. So, a deep analysis needs to be perform in order to have a global view before starting to refactor a code. 

### How do these pros and cons apply to refactoring the original VBA script?

The main advance is that the code and terms we had to preformed were already viewed in the module, so it was easy the make to update and run the analysis to have the same result. it helps me a lot on this analysis 
The main disadvantage is that the code we had to refactor comes with some defined variable that we had to amend or remove in order to run the code. 
For Example 'Dim startTime As Single and 'Dim endTime  As Single were in the code and the same time I had to create Dim tickerStartingPrices As Single end Dim tickerEndingPrices As Single.
So, when run the code to calculate the return on the refactored analysis I face a bug, this can be led to the face that the code I used also registered the previous variable. So, it’s importing to delete or put in comment all the variable we have to update, or we do not use when to refactor a code.

 
 
