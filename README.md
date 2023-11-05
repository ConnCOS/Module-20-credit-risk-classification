# Module-20-credit-risk-classification
This Challenge requires using various techniques to train and evaluate a model based on loan risk.
A dataset of historical lending activity from a peer-to-peer lending services company serves as the foundation to build a model that can identify the creditworthiness of borrowers.

# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


















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

