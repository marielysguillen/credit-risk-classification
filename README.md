# credit-risk-classification
Using Python and supervised learning


Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

Requirements
Split the Data into Training and Testing Sets 
Read the lending_data.csv data from the Resources folder into a Pandas DataFrame. 
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. 
Split the data into training and testing datasets by using train_test_split. 

Create a Logistic Regression Model:
Fit a logistic regression model by using the training data (X_train and y_train). 

Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model. 
Evaluate the model’s performance by doing the following:

Generate a confusion matrix. 
Generate a classification report. 
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? 

Write a Credit Risk Analysis Report:
Provide an overview that explains the purpose of this analysis. 

Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. 

Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. 

Coding Conventions and Formatting 
Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants. 

Name functions and variables with lowercase characters, with words separated by underscores. 

Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code. 

Use concise logic and creative engineering where possible. 



Credit Risk Analysis Report:

Purpose of Analysis: 
The aim of this analysis is to develop and assess the accuracy of a data model designed to predict the creditworthiness of potential borrowers in peer-to-peer lending services. 

Results:
Predicting healthy loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans. 
Accuracy 94%
The model had 100% recall in predicting healthy loans, and 95% recall in predicting high-risk loans

Summary:
The dataset, underwent a split into training and testing sets. Utilizing the machine learning technique, LogisticRegression module from scikit-learn, an initial logistic regression model was constructed using the training set. Subsequently, this model was applied to the testing dataset to ascertain whether a loan to a borrower would be categorized as healthy-risk or high-risk.
For healthy loans, the model achieves perfect precision, recall, and F1-score, indicating that it accurately identifies all instances of healthy loans in the dataset without any false positives or false negatives.
Regarding high-risk loans, the model maintains high precision (0.87), suggesting that when it predicts a loan as high-risk,
It is correct approximately 87% of the time. Additionally, it demonstrates high recall (0.95), indicating that it effectively captures 95% of actual high-risk loans. The F1-score, a balanced measure of precision and recall.

 
