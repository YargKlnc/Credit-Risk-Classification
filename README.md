# Loan Risk Prediction Analysis

by YK, UofT

![image](https://github.com/YargKlnc/credit-risk-classification/assets/142269763/b5c1216e-3aba-4ad6-a568-9e3a766ba089)


**Background**

Using various techniques to train and evaluate a model based on loan risk with a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


**Tasks and Implementation**

The tasks are divided into three main sections:

  1- Data Split into Training and Testing Sets

  2- Logistic Regression Model Created with the Original Data

  3- Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis is to measure and compare the performance of a logistic regression model in predicting loan risks. Two instances of the model were evaluated: one trained on the original dataset, and the other on oversampled data. The goal is to assess the impact of oversampling on the model's ability to predict healthy (low-risk) and high-risk loans.

## Results

### Original Dataset Model:

- **Balanced Accuracy:** 95%
- **Precision (Healthy Loans):** 100%
- **Recall (Healthy Loans):** 99%
- **F1-Score (High-Risk Loans):** 88%

### Oversampled Dataset Model:

- **Balanced Accuracy:** 99%
- **Precision (Healthy Loans):** 100%
- **Recall (Healthy Loans):** 99%
- **F1-Score (High-Risk Loans):** 91%

## Summary

The logistic regression model, when trained on the original dataset, demonstrated solid performance with a balanced accuracy of 95%. However, with oversampled data, the model's balanced accuracy significantly improved to 99%, indicating enhanced predictive capabilities.

For healthy loans (label `0`), both models achieved perfect precision (100%) and high recall (99%), implying a low rate of false positives and false negatives. This suggests that the models are effective in correctly identifying and accepting healthy loans.

In terms of high-risk loans (label `1`), the oversampled model outperformed the original model, achieving a higher F1-score (91% compared to 88%). This indicates better balance between precision and recall for identifying high-risk loans.

## Recommendation

Considering the improved performance metrics, especially the increased balanced accuracy and F1-score for high-risk loans with oversampling, it is recommended to use the logistic regression model trained on oversampled data. This model showcases enhanced accuracy and reliability in predicting both healthy and high-risk loans, making it a more robust choice for loan risk assessment. The company can benefit from the improved predictive power of this model to make more informed decisions regarding loan approvals.


**Tasks Accomplished**


*Splitting the Data into Training and Testing Sets:*

• Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

• Created the labels set (y) from the “loan_status” column, and then created the features (X) DataFrame from the remaining columns.

• Split the data into training and testing datasets by using train_test_split.



*Creating a Logistic Regression Model:*

• Fitted a logistic regression model by using the training data (X_train and y_train).

• Saved the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.

• Evaluated the model’s performance:

o Generated a confusion matrix.

o Generated a classification report.

o Answered the following question: How well did the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?



*Credit Risk Analysis Report:*

• Provided an overview that explains the purpose of this analysis.

• Using a bulleted list, described the accuracy, precision, and recall scores of the machine learning model.

• Summarized the results from the machine learning model. Included justification for recommending the model for use by the company. If not recommending the model, justified the reasoning.


# References

Head photo rights belongs to https://www.au-group.com/



