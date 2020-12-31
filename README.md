# House Price Prediction using Regression Algorithms

The following repository contains analysis on the House Price Prediction dataset available on Kaggle. Based on supervised regression algorithms, optimal prices were predicted. The dataset can be found on: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview. 

## Introduction 

The project aims to analyse the House Price Prediction dataset to assess the features that influence a home buyer would like to know about a property. There are 4 key parts of the project:

Data Exploration and Preparation 
Data Preprocessing (feature engineering, univariate and bivariate analysis)
Exploratory Data Analysis 
Modelling and Predictiong 

Based on these steps, supervised and unsupervised machine learning algorithms like Linear Regression, Logistic Regression, Lasso and Ridge Regression were applied to predict house prices based on features like year built, total square feet, garage area, sale type, sale condition and overall quality. 

## Analysis 

I first performed data wrangling on 1,500 records to eliminate N/A and missing values to perform further analysis on the data. The next step was to visualise the data to find relationship between variables as well as underlying trends. Based on correlation heatmap, I selected the variables to be used in the model and removed any outliers that could hinder the analysis. On conducting univariate analysis on the target variable - Sale Price - it was found that it had positive skewness and leptokurtic distribution which was then reduced by log transformation. Using the training set, I applied supervised machine learning models. I built 4 models: Simple Linear Regression, Logistic Regression, Lasso and Ridge Regression. 

## Outcome 

While the Logistic Regression model gave the highest accuracy but also the highest mean squared error, the Ridge Regression model gave the lowest mean squared error with an accuracy of 64%. It was interesting to note that while the accuracy ranged from 40-60% for other models; logistic regression gave an overall higher accuracy of 80%. Based on this finding, I believe Ridge Regression gave the closest predictions with the lowest mean squared error of 10% and an optimal accuracy of 64%. 
