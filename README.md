# Stock Price Prediction Using Different Regression Models

## Overview

This repository hosts a machine learning project focused on predicting stock prices using a variety of regression algorithms. The project utilizes historical stock price data and relevant features to build and evaluate regression models for accurate price prediction. The primary objective is to explore different regression techniques and assess their performance in predicting stock prices.


  ## Dataset
  [World Stock Prices Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/world-stock-prices-daily-updating)

  The dataset used for this project includes the following features:
- Date: The date of the stock price data.
- Open: The opening price of the stock on that date.
- High: The highest price the stock reached during the trading day.
- Low: The lowest price the stock reached during the trading day.
- Close: The closing price of the stock on that date.
- Volume: The trading volume, i.e., the number of shares traded on that date.

## Regression Models Explored

The project explores the following regression models:

1. **Linear Regression**
   - A basic linear approach to modeling the relationship between the dependent variable (stock price) and one or more independent variables.

2. **Logistic Regression**
   - Despite its name, logistic regression is commonly used for binary classification. In this context, it may be applied for certain stock price prediction scenarios.

3. **Decision Tree Regression**
   - A tree-like model of decisions that can be useful for capturing complex relationships in the data.

4. **K-Nearest Neighbors (KNN) Regression**
   - A non-parametric method that makes predictions based on the average of the 'k' nearest neighbors.

5. **Ridge Regression**
   - A regularization technique that aims to prevent multicollinearity in multiple regression data.

6. **Lasso Regression**
   - Similar to Ridge Regression, Lasso Regression also involves regularization, but it tends to produce sparse coefficient estimates, effectively performing feature selection.

7. **Bayesian Ridge Regression**
   - A Bayesian approach to linear regression, incorporating regularization to stabilize the model.

8. **Polynomial Regression**
   - An extension of linear regression, where polynomial features are included to capture more complex relationships in the data.

    


