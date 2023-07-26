# Housing Price Prediction Assignment- Advanced Regression

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

### Introduction
This is an programatic Assignment with an objective to build a advanced linear regression model for the prediction of House Price using Ridge & Lasso regression.

### Background:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know the following things about the prospective properties:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
### The variables significant in predicting the price of a house are:

- 1stFlrSF
- 2ndFlrSF
- OverallQual
- OverallCond
- SaleCondition_Partial
- LotArea
- BsmtFinSF1
- SaleCondition_Normal
- MSZoning_RL
- Neighborhood_Somerst

### How well those variables describe the price of a house?
- Unit Change in '1stFlrSF':
  If the feature '1stFlrSF' increases by one unit (e.g., one square foot), the natural logarithm of the SalePrice will increase by approximately 0.124911, assuming all other features remain constant.

- Negative Sign of the Coefficient:
  Since the coefficient for '1stFlrSF' is positive (0.124911), this implies that an increase in the '1stFlrSF' feature is associated with an increase in the natural logarithm of the SalePrice. However, a negative sign in the coefficient signifies a negative correlation between the predictor and the target variable.

- Converting Predicted Values to Original Scale:
  To get the predicted SalePrice values in the original scale (not the natural logarithm scale), we need to perform the antilog (exponentiation) on the predicted values.

### Optimal value of lambda for Ridge Regression = 9
### Optimal value of lambda for Lasso = 0.0001

## Technologies Used
- Python     - version 3.8.3
- NumPy      - version 1.24.3
- Pandas     - version 1.5.3
- Matplotlib - version 3.2.2
- Seaborn    - version 0.12.2
- Warnings
- Statsmodels

## Acknowledgements
- This project was done as an Assigment by Upgrad and IIIT-B.
- This project was based House Price Prediction Assignment which was part of Advanced Linear Regression.
- I would like to Thank my teachers & my peer-students whos supported me to complete this assignment.

## Contact
Created by Rakesh Rajan-(https://github.com/rrajanml) feel free to contact me!
