# Credit Risk Classification Analysis

## Overview of the Analysis

The purpose of this analysis is to evaluate the creditworthiness of borrowers using historical lending data from a peer-to-peer lending service. A logistic regression model was employed to predict whether a loan is classified as "healthy" (low risk of default) or "high-risk" (high risk of default) based on features such as loan size, interest rate, borrower income, and others.

## Results

The following metrics summarize the model's performance:

- **Accuracy:** 99%  
  The model accurately classified 99% of the loans in the test set.
  
- **Precision (High-Risk Loans):** 86%  
  When the model predicted a loan as high-risk, it was correct 86% of the time.

- **Recall (High-Risk Loans):** 91%  
  The model correctly identified 91% of the actual high-risk loans.

- **F1-Score (High-Risk Loans):** 88%  
  The F1-score, which balances precision and recall, was 88% for high-risk loans.

## Summary

The logistic regression model performed very well in classifying both healthy and high-risk loans, with an overall accuracy of 99%. The model's precision and recall for high-risk loans were both strong, meaning it correctly identified most high-risk loans and made relatively few mistakes when predicting them.

Given the high accuracy and a good balance between precision and recall for high-risk loans, this model can be recommended for use in identifying credit risk. However, since there is still a small percentage of high-risk loans that are misclassified as healthy, it may be beneficial to explore techniques like balancing the dataset or using more complex models to improve the recall even further.
