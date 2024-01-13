# Credit-Risk-Classification

Credit Risk Classification & Analysis by YK, UofT

![image](https://github.com/YargKlnc/credit-risk-classification/assets/142269763/b5c1216e-3aba-4ad6-a568-9e3a766ba089)


**Background**

Using various techniques to train and evaluate a model based on loan risk with a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


**Instructions**

The instructions for this Challenge are divided into the following subsections:

•	Split the Data into Training and Testing Sets

•	Create a Logistic Regression Model with the Original Data

•	Write a Credit Risk Analysis Report


# 1- Split the Data into Training and Testing Sets


Open the starter code notebook and use it to complete the following steps:


1.	Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
  

2.  Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
   

NOTE: A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.


3.	Split the data into training and testing datasets by using train_test_split.


# 2- Create a Logistic Regression Model with the Original Data

Use your knowledge of logistic regression to complete the following steps:

1.	Fit a logistic regression model by using the training data (X_train and y_train).

2.	Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

3.	Evaluate the model’s performance by doing the following:

  o	Generate a confusion matrix.

  o	Print the classification report.

4.	Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?


# 3- Write a Credit Risk Analysis Report


Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.


Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

1.	An overview of the analysis: Explain the purpose of this analysis.

2.	The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

3.	A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


**Requirements**


*Split the Data into Training and Testing Sets:*

•	Read the lending_data.csv data from the Resources folder into a Pandas DataFrame

•	Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns

•	Split the data into training and testing datasets by using train_test_split


*Create a Logistic Regression Model*

•	Fit a logistic regression model by using the training data (X_train and y_train)

•	Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model

•	Evaluate the model’s performance by doing the following:

  o	Generate a confusion matrix

  o	Generate a classification report

  o	Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?


*Write a Credit Risk Analysis Report*

•	Provide an overview that explains the purpose of this analysis

•	Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model

•	Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning



# References

Head photo rights belongs to https://www.au-group.com/



