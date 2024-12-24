# Bike Sharing Linear Regression Model Assignment

> A Multiple Linear Regression model assignment to understand Rental bikes demand prediction 
## Table of Contents

- [General Info](#general-info)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## General Info

### Project Background

This is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes. The Model prediction aims to help business make better decisions by understanding the high demand on multiple features.

### Business Problem

To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

### Dataset

The analysis uses a day dataset containing 731 records with the following key features:
- cnt and year-2018,2019
- season: season (1: spring, 2: summer, 3: fall, 4: winter)
- weekday, working day, temperature

## Technologies Used

- Python - version 3.12
- pandas - version 2.1.1
- numpy - version 1.24.3
- matplotlib - version 3.8.0
- seaborn - version 0.12.2
- sklearn, statsmodels, MinMaxScaler, train_test_split, variation_inflation_factor, r2_score, RFE, LinearRegression libraries

## Features

- Comprehensive data cleaning and preprocessing
- Exploratory Data Analysis (EDA) including:
  - Univariate analysis 
  - Bivariate analysis 
  - Correlation analysis of numerical variables
- Visual analysis using various plot types
- Creating dummy variables
- Scaling the variables
- Splitting the training and test sets
- Training the model:
  - RFE (Recursive Feature Elimination)
  - VIF (Variance Inflation Factor)
  - Residual analysis
- Making Predictions
- Model Evaluation

## Conclusions

The linear regression model exhibits a strong correlation with the rental count, achieving an R-squared value of 0.822. This indicates that approximately 82.2% of the variance in the rental count can be explained by the independent variables included in the model. Key predictors include year (yr), holiday status, temperature (temp), windspeed, weather situation (specifically rain/snow and clear weather), and season (summer, fall, and winter). Further analysis using VIF (Variance Inflation Factor) identified 'hum' (humidity) as having multicollinearity and was removed. Residual analysis supported the model's overall validity.

## Acknowledgements

- Analysis inspired by management best practices
- Methodology based on Linear regression model techniques

## Contact

Created by Sujana Anche - feel free to contact!
