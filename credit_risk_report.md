# Credit Risk Classification Report

## Overview of the Analysis

* The purpose of this analysis is to provide predictions about loan health based on interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.
* A loan status value of 0 indicates a healthy loan, whereas a loan status value of 1 indicates a loan that is at-risk.
* In order to analyze this data using machine learning it had to be split into training and testing data sets, then a logical regression model was created and fit using the testing and training data, a confusion matrix and classification report were then created to learn how well the model performed.

## Results

* Logistic Regression Model (healthy loan):
    * Accuracy: .99
    * Precision: 1.00
    * Recall: 1.00
* Logistic Regression Model (At-risk Loan):
    * Accuracy: .99
    * Precision: .87
    * Recall: .95

## Summary

* The model worked well for predicting both healthy loans and at-risk loans, though the precision for healthy loans was significantly better than the precision for at-risk loans. The proper course of action in this case would be to use the model to predict healthy loans, but use this model in conjunction with another for predicting at-risk loans. The reasoning for this being that it is in the bank's best interest to ensure they are not denying applicants who are not at risk.