# Credit_Risk_Analysis

## Overview of the analysis: 

The purpose of this anaylsis was to explore different machine learning models to observe the differences in accuracy and percision. This was done using a LoanStats_2019Q1.csv and preidicting whether a person was high risk or low risk based on various factors.

## Results

### Native random oversampling 
* Accuracy score of 64.63%.
* percision rating of 100% for low risk, and 1% for high risk.
### SMOTE oversampling 
* Accuracy score of 65.86%.
* percision rating of 100% for low risk, and 1% foer high risk.
### ClusterCentorids
* Accuracy score of 65.86%.
* percision rating of 100% for low risk, and 1% for high risk.
### SMOTEEN
* Accuracy score of 54.42%.
* percision rating of 100% for low risk, and 1% for high risk.
### BalancedRandomForest
* Accuracy score of 78.85%.
* percision rating of 100% for low risk, and 3% for high risk
* BRFC mdel cited .total_rec_prncp as the main feature of importance citing it at 7.8%.

![Ranking of important factors](https://github.com/ChristopheGarcia1/Credit_Risk_Analysis/blob/main/important_features.png)
### Easy Ensemble AdaBoost 
* Accuracy score of 93.16%
* percision rating of 100% for low risk, and 3% for high risk


## Summary

 From the results above the best model to use for predictive modeling for calculated loan risk would be the Easy Ensemble AdaBoost model since it had an accuracy of 93.16% when it came to predicting risk. While this is higher than the rest, it is still a 7% margin of error that can in the long run cause losses. 