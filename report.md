# Module 12 Report 

## Overview of the Analysis
In this analysis, the goal was to build a machine learning model that can predict the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company. The purpose of the analysis is to identify borrowers who are likely to default on their loans (high-risk) versus those who will repay their loans (healthy).

The data used in this analysis includes financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable, loan_status, indicates whether a loan is healthy (0) or high-risk (1).
Stages of the machine learning process included:

1. Reading and preprocessing the data.
2. Splitting the data into training and testing sets.
3. Training a Logistic Regression model using the training data.
4. Making predictions on the test data.
5. Evaluating the model's performance using metrics such as confusion matrix, accuracy, precision, and recall.

## Results
####  Machine Learning Model 1: Logistic Regression
###  Accuracy: 0.99
### Precision:
* Healthy loans (0): 1.00
* you  High-risk loans (1): 0.86
### Recall:
* Healthy loans (0): 0.99
* High-risk loans (1): 0.94
### F1-Score:
* Healthy loans (0): 1.00
* High-risk loans (1): 0.90

## Summary


The Logistic Regression model demonstrates excellent performance, with an overall accuracy of 99%. The precision and recall scores for predicting healthy loans are perfect, indicating that the model accurately identifies healthy loans with no false positives and very few false negatives. For high-risk loans, the model shows strong performance, with a high recall of 94% and a precision of 86%. This means the model is very effective in identifying high-risk loans, with a small number of false positives.


Based on the results, I recommend using the Logistic Regression model for assessing loan risks. The model performs exceptionally well in predicting healthy loans and shows strong performance in identifying high-risk loans. Given the high recall for high-risk loans, the model is reliable for identifying borrowers who are likely to default, which is crucial for the company's risk management.

While the model performs well, it's important to monitor its performance over time and retrain it periodically with new data to maintain its accuracy and effectiveness. Additionally, depending on the company's priorities, further tuning might be necessary to balance precision and recall for high-risk loans.










