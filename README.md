# Module-20-credit-risk-classification
This challenge requires using various techniques to train and evaluate a model based on loan risk.
A dataset of historical lending activity from a peer-to-peer lending services company serves as the foundation to build a model that can identify the creditworthiness of borrowers.

# Module 20 Report Template

## Overview of the Analysis
This analysis employed a supervised machine learing model to predict whether a loan was healthy or high-risk. A csv file containing 75,536 entries detailing loan features such as loan amount, interest rate, borrower's incomes and debt-to-income ratio provided the original data which by loan status was marked as a binary classification with 0 being healthy and 1 high-risk.
Data was separated into labels and features, using the y variable for loan status and the other financial categories as features. Data was then split into training and testing datasets using the sklearn train_test_split module. Two logistic regression models were developed, one using the original data to a fitted model and a second using resampled data employing the RandomOverSampler module.

## Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
Balanced Accuracy Score: 99.2% -- this measures the sensitivity of a true positive rate against the specificity of a true negative rate against two imbalanced classes -- in this case the high number of healthy loans vs. the lower rate of high-risk loans. A score of 99.2% This score is .08 from 1, meaning it is highly effective atcorrectly classifying data observations.
Precision Score: 1.0 for healthy loans and .87 for high-risk loans. Again, the closer to a score of 1, the better the model has accurately evaluated the data.
Recall Score: 1.0 for healthy and .89 for high-risk

* Machine Learning Model 2:
Balanced Accuracy Score: Slightly higher than the first model at 99.4% 
Precision Score: In this model, the slightest degradation to .99 from 1.0 for healthy loans but a noticeable gain for high-risk loan prediction to .99 from .87 in the first model. 
Recall Score: .99 for both.

## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
For loan-risk assessment purposes, the recommended model would be for the RandomOverSampler module, which analyzed a higher number of loan applications and had a significantly higher accuracy rate for healthy and high-risk loans for precision, recall, f1-score and balanced accuracy. Given the higher stakes of funding high-risk loans, a more accurate prediction rate for those loans is more important for any financial institution wanting to assess risk and potential loan default.

















## Instructions:
### Split the Data into Training and Testing Sets
### Create a Logistic Regression Model with the Original Data
### Write a Credit Risk Analysis Report
## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:
Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
Split the data into training and testing datasets by using train_test_split.
## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
Fit a logistic regression model by using the training data (X_train and y_train).
Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following:
Generate a confusion matrix.
Print the classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

