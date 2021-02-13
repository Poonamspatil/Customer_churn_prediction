# Customer Churn Prediction
### Using support vector classifier

## Table of contents
* [Introduction](#introduction)
* [Data](#data)
* [Description](#description)

## Introduction
Reducing customer churn is crucial to the health of any business. Customer churn prediction techniques attempt to understand customer behaviors and attributes which signal the risk and timing of customer churn. 

This project aims to predict whether a customer will churn given a set of predictors. The project explores Support vector machine (SVM) for binary classification probelm using different kernels (linear, polynomial, radial basis) and compares classification results with Logistic regression as a baseline model. Classification error is the metric used for model selection. Result shows that SVM with radial basis function kernel is the most optimal model as judged by classification error, with error rate of 0.21%. The results can be used by bank officials and general managers to accurately determine the customer churn rate and design strategies for customer retention.

## Data:
The customer churning dataset is obtained from Kaggle (https://www.kaggle.com/blastchar/telco-customer-churn).

