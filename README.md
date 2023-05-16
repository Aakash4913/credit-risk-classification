# credit-risk-classification


Overview

The purpose of this analysis is to build a logistic regression model to predict credit risk based on a dataset of lending data. We will use this model to classify loans as either healthy (0) or high-risk (1), based on a variety of factors.

Methodology

We will follow the steps outlined below to build and evaluate our logistic regression model:

Split the Data into Training and Testing Sets
We will use the lending_data.csv file from the Resources folder and split the data into training and testing sets using the train_test_split function from scikit-learn.

Create a Logistic Regression Model with the Original Data
We will create a logistic regression model using the training data and then evaluate its performance by generating a confusion matrix, calculating the accuracy score, and printing the classification report.

Predict a Logistic Regression Model with Resampled Training Data
We will create a new logistic regression model by oversampling the minority class and then evaluating its performance using the same metrics as above.

Write a Credit Risk Analysis Report
Finally, we will write a brief report summarizing and analyzing the performance of the machine learning models used in this analysis.

Results

We have created two logistic regression models to predict credit risk. Here are the performance metrics for both models:

Original Data Model
Accuracy Score: 0.99
Precision Score: 0.87
Recall Score: 1.00


Resampled Data Model
Accuracy Score: 1.00
Precision Score: 0.87
Recall Score: 1.00
Summary

Both models performed well, with the resampled data model having higher accuracy. 