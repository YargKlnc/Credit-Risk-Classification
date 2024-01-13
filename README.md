# Credit-Risk-Classification

Credit Risk Classification & Analysis by YK, UofT

![image](https://github.com/YargKlnc/credit-risk-classification/assets/142269763/b5c1216e-3aba-4ad6-a568-9e3a766ba089)


**Background**

Using various techniques to train and evaluate a model based on loan risk with a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


**Instructions and Implementation**

The instructions for this Challenge are divided into three main sections:

# 1- Data Split into Training and Testing Sets

## Instructions:

1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
   
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
   
   *Note: A value of 0 in the “loan_status” column means that the loan is healthy, while a value of 1 indicates a high risk of defaulting.*

3. Split the data into training and testing datasets by using train_test_split.

## Implementation:

1. The lending_data.csv data was successfully read from the Resources folder into a Pandas DataFrame.

2. The labels set (y) and features set (X) were created, distinguishing between healthy loans (0) and high-risk loans (1).

3. The data was effectively split into training and testing datasets using the train_test_split method.


# 2- Logistic Regression Model Created with the Original Data

## Instructions:

1. Fit a logistic regression model by using the training data (X_train and y_train).

2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

3. Evaluate the model’s performance by doing the following:

   - Generate a confusion matrix.
   - Print the classification report.

4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Implementation:

1. A logistic regression model was successfully fitted using the training data (X_train and y_train).

2. Predictions for the testing data labels were saved using the testing feature data (X_test) and the fitted model.

3. Model performance was evaluated, resulting in the generation of a confusion matrix and the printing of a classification report.

4. The logistic regression model demonstrated effective prediction for both healthy loans (0) and high-risk loans (1).


# 3- Credit Risk Analysis Report

## Instructions:

Write a brief report in the README.md file included in your GitHub repository, adhering to the following structure:

1. An overview of the analysis: Explain the purpose of this analysis.

2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

## Implementation:

The analysis README.md file was created, providing the following:

1. An overview was presented, explaining the purpose of the credit risk analysis.

2. Results were summarized in a bulleted list, describing the accuracy score, precision score, and recall score of the logistic regression model.

3. A comprehensive summary of the machine learning model results was provided, along with a justified recommendation for its use by the company, showcasing the effectiveness of the approach.


**Tasks Completed**

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



