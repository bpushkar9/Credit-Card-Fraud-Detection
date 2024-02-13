# FindDefault: (Prediction of Credit Card Fraud)
## Problem Statement:
A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 

We have to build a classification model to predict whether a transaction is fraudulent or not.
## About the Dataset:
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

The dataset contains only numerical input variables which are the result of a PCA transformation. Considering the confidentiality issues, it is understood that the original features and more background information about the data cannot be provided. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 in case of a legit transaction.
## Project Focus:
We're going to focus on the following steps in order to solve the problem of detecting fraudulent credit card transactions:
### 1. Exploratory Data Analysis:
Analyze and understand the data to identify patterns, relationships, and trends in the data by using Descriptive Statistics and Visualizations.
### 2. Data Cleaning:
This might include standardization, handling the missing values and outliers in the data. 
### 3. Dealing with Imbalanced Data:
This data set is highly imbalanced. The data should be balanced using the appropriate methods before moving onto model building.
### 4. Feature Engineering:
Create new features or transform the existing features for better performance of the ML Models. 
### 5. Model Selection:
Choose the most appropriate model that can be used for this project.
### 6. Model Training:
Split the data into train & test sets and use the train set to estimate the best model parameters.
### 7. Model Validation:
Evaluate the performance of the model on data that was not used during the training process. The goal is to estimate the model's ability to generalize to new, unseen data and to identify any issues with the model, such as overfitting.

