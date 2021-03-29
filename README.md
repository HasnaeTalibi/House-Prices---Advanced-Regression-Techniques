# House-Prices---Advanced-Regression-Techniques


## Overview
There are several factors that influence the price a buyer is willing to pay for a house. Some are apparent and obvious and some are not. Nevertheless, a rational approach facilitated by machine learning can be very useful in predicting the house price. A large data set with 79 different features (like living area, number of rooms, location etc) along with their prices are provided for residential homes in Ames, Iowa. The challenge is to learn a relationship between the important features and the price and use it to predict the prices of a new set of houses.

## Repository structure
1. EDA: Exploratory data analysis

Plot distribution of the numerical features examine the skewness Plot correlation matrix between the features

2. cleaning Data: Cleaning and preprocessing of data

- Remove skewenes of target features 
- Handle missing values in categorical features 
- Transformation some categorical features (with specific order) into numerical
- Transformation of some numerical features that are actually categorical: ['MSSubClass', 'OverallCond’]
- Handle missing values in numerical features 
- Feature selection
- One-Hot Encoding for categorical data
- Transformation of skewed features:
      - SalePrice – log transformation
      - Other features with skeweness > 0.5 using BoxCox transformation


3. Feature Engineering: Engineering new features

4. Modeling: Fitting different models on the cleaned data and predict the house price on test set

## Contributors
Hasnae Talibi


Transformation of skewed features:
SalePrice – log transformation
Other features with skeweness > 0.5 using BoxCox transformation
Transformation some categorical features (with specific order) into numerical

