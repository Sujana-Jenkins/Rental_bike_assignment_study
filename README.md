# Bike Sharing Assignment

> A Multple Linear Regression model assignment to understand Rental bikes demand prediction 
> factors using historical lending data.

## Table of Contents

-   [General Info](#general-information)
-   [Technologies Used](#technologies-used)
-   [Features](#features)
-   [Conclusions](#conclusions)
-   [Acknowledgements](#acknowledgements)

## General Information

### Project Background

This is a programming assignment wherein we have to build a 
multiple linear regression model for the prediction of demand
for shared bikes.The Model prediction  aims to help business
make better decisions by understanding the high demand on multiple features.

### Business Problem

To model the demand for shared bikes with the available independent variables. 
It will be used by the management to understand how exactly the demands vary 
with different features. They can accordingly manipulate the business strategy 
to meet the demand levels and meet the customer's expectations. 

### Dataset

The analysis uses a day dataset containing 731 records with the
following key features: - cnt and year-2018,2019
season : season (1:spring, 2:summer, 3:fall, 4:winter)
weekday,working daytemperature


## Features

-   Comprehensive data cleaning and preprocessing
-   Exploratory Data Analysis (EDA) including:
    -   Univariate analysis of loan amounts and interest rates
    -   Bivariate analysis of loan status vs. various features
    -   Correlation analysis of numerical variables
-   Visual analysis using various plot types
-   Creating dummy variebles
-   Scaling the variebles
-   Splitting the training and test sets
-   Training the model
    - RFE
    - VIF
    - Residul analysis
-   Making Predictions
-   Model Evaluation

## Conclusions

we can see that equation of our best fitted line is:
Rental count = 0.2341yr - 0.0872 * Holiday + 0.4662temp - 0.1546 * windspeed - 0.0750 * windspeed -0.2785* Rain/Snow + 0.1209* Summer + 0.0827* fall + 0.1572* winter

#The linear regression model exhibits a strong correlation with the rental count, achieving an R-squared value of 0.822. This indicates that approximately 82.2% of the variance in the rental count can be explained by the independent variables included in the model. Key predictors include year (yr), holiday status, temperature (temp), windspeed, weather situation (specifically rain/snow and clear weather), and season (summer, fall, and winter). Further analysis using VIF (Variance Inflation Factor) identified 'hum' (humidity) as having multicollinearity and was removed. Residual analysis supported the model's overall validity.

## Technologies Used

-   Python - version 3.12
-   pandas - version 2.1.1
-   numpy - version 1.24.3
-   matplotlib - version 3.8.0
-   seaborn - version 0.12.2
-   sklearn,statsmodels,MinMaxscaler,train_test_split,variation_inflation_factor,r2_score,RFE,LinearRegression libraries

## Acknowledgements

-   Analysis inspired by  management best practices
-   Methodology based on Linear regression model techniques

## Contact

Created by Sujana Anche - feel free to contact!
#   R e n t a l B i k e A s s i g n m e n t  
 "# RentalBikeAssignment" 
