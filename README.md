# Fraud-Detection

## Introduction
A machine learning classifer to detect fraudulent transactions specific to credit cards. This is part of the Udacity Machine Learning Engineer Nanodegree program. 

## Description


## Dataset
The dataset used to train and evaluate the model is obtained from kaggle [here](https://www.kaggle.com/mlg-ulb/creditcardfraud). The datasets contain transactions made by credit cards in September 2013 by european cardholders over 2 days. 

There are 492 transactions labeled as fraudulent, out of the 284,807 transactions, making our dataset highly imbalanced. 

It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the authors cannot provide the original features and more background information about the data.

Features `V1, V2, ... V28` are the principal components obtained with PCA, the only features which have not been transformed with PCA are `Time` and `Amount`. 

`Time` contains the seconds elapsed between each transaction and the first transaction in the dataset. `Amount` is the transaction amount. `Class` is the target variable; with `1` being fradulent and `0` being non-fraudulent.


