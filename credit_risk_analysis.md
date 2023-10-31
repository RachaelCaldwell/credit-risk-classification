# Module 20 Credit Risk Report 

## Overview of the Analysis

The purpose of this analysis is to build and evaluate machine learning models for predicting loan status based on financial information. The analysis aims to assess the performance of these models and determine which one is more suitable for making predictions regarding loan approval or denial.

***Financial Information in the Data:***
- The data includes features (independent variables) that describe loan applicants' financial situations, and the target variable is 'loan_status,' which represents whether a loan application was approved or denied.

***Variables:***
- Loan Status (loan_status): The variable to be predicted, with values 0 (rejected) and 1 (approved).

***Methods Used:***
- Logistic Regression: Used for both Model 1 and Model 2 to predict loan status.
- Random Oversampling: Applied to address class imbalance in the data.

## Results

***Machine Learning Model 1:***
- Balanced Accuracy: 0.952
- Precision (Class 0): 1.00
- Precision (Class 1): 0.85
- Recall (Class 0): 0.99
- Recall (Class 1): 0.91

***Machine Learning Model 2:***
- Balanced Accuracy: 0.995
- Precision (Class 0): 0.99
- Precision (Class 1): 0.99
- Recall (Class 0): 0.99
- Recall (Class 1): 0.99

## Summary
- Machine Learning Model 2 (Logistic Regression with Resampled Data) performs significantly better than Machine Learning Model 1 (Logistic Regression without resampling) in terms of balanced accuracy, precision, and recall for both classes. Model 2 has a balanced accuracy score close to 1, indicating it performs very well in correctly predicting both loan approvals and denials.
- The performance depends on the problem at hand. If the goal is to make better loan approval decisions while considering both precision and recall for both approved (1) and rejected (0) loans, Model 2 is recommended. It achieves higher accuracy and balance in class predictions, making it a more reliable choice for creditworthiness assessment.
- In summary, Model 2, which uses resampling to address class imbalance, is the better choice for making lending decisions as it provides a more balanced and accurate prediction of loan approval or rejection.
