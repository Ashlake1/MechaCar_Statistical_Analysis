# MechaCar_Statistical_Analysis

## Overview


## Deliverable 1: Predict MPG using Linear Regression
![D1_linear_regression.png](/Resources/D1_linear_regression.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The non-random amounts of variance variables are vehicle length and ground clearance as indicated by the low p-value when applied to the mpg.

Q: Is the slope of the linear model considered to be zero? Why or why not?
A: The slope is NOT zero, in fact is smaller than a level of 0.05 thus rejecting the null hypothesis.

Q:  Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
A: This is effective as the linear regression shows the R-squared value is about 70% of the MPG.


## Deliverable 2: Suspension Coils Summary

## Summary Statistics on Suspension Coils
![D2_lot_summary.png](/Resources/D2_lot_summary.png)


![D2_total_summary.png](/Resources/D2_total_summary.png)

Q: There is a summary that addresses the design specification requirement for all the manufacturing lots and each lot individually
A: The hypothesis is true for Lot1 and Lot2, however Lot3 shows too much variance on PSI and fails to prove the hypothesis.



## Deliverable 3: T-Tests on Suspension Coils

- There is a summary of the t-test results across all manufacturing lots and for each lot.

![ttest_all.png](/Resources/ttest_all.png)

![ttest_lot1.png](/Resources/ttest_lot1.png)

![ttest_lot2.png](/Resources/ttest_lot2.png)

![ttest_lot3.png](/Resources/ttest_lot3.png)

All lots p-value is 1 indicating that there is not difference between lots PSI. The p-value for lot1 is the same as the All_lots p_value. Lot2 does not have the same p_value as lot_1 but still accepts the hypothesis. Unfortunately, the p-value of lot_3 is less than .05 indicting a rejection of the hypothesis.



## Deliverable 4: Mecha Car Versus Competiton

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:

Q: What metric or metrics are you going to test?
- Cost
- Horsepower 
- MPG/Fue Efficiency 

Q: What is the null hypothesis or alternative hypothesis?
A: The Null Hypothesis: MechaCar's fuel efficiency is affected by weight in a similar way as the competitors fuel efficiency is affected by weight.

Q: What statistical test would you use to test the hypothesis? And why?
A: You would want to use a two sample t-test in order to gather statistical significance.

Q: What data is needed to run the statistical test?
A: We would need average mpg used on multiple trips with same weight being carried from both competitors and the MechaCar prototypes. 