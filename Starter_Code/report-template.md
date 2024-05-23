# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis:
    This analysis uses a machine learning model to predict the creditworthiness of loan applicatns using historical lending data. The analysis seeks to guide the lendor in making informed decisions regarding loan approvals for high-risk applicants. 
* Explain what financial information the data was on, and what you needed to predict:
    The dataset contains data on various aspects of a loan, inclduing interest rate, borrower income, debt to income ratio, and more.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`):
    The target variable (y) was "loan_status", where 0 represnts a healthy loan, and 1 represents a high risk loan, and "value_counts" 
* Describe the stages of the machine learning process you went through as part of this analysis:
    1) Load in data from CSV
    2) separate target variable (y) and feature variables (x)
    3) split data in to training and test sets. 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    In this MLM we used the LogisticRegression alogorithm to traing the model.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
        Accuracy: The weighted accuracy was 99% 
        Precision: healthy loans had a 100% precision, and high risk loans had an 86% precision.
        Recall: healthy loans had a 100% recall, and high risk loans had a 91% recall. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?:
    The logistic regression model performed very well, achieving very high accuracy, precision, and recall scores. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ):
    The performance depends on the desired outcome of the model. If the goal is to evaluate high risk loans, then it would make sense to prioritize high recall scores for high-risk loans to ensure fewer risky loans are missed.

If you do not recommend any of the models, please justify your reasoning.
