# Advance Regression Assignment 

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia. The dataset has been provided.
The company is looking at prospective properties to buy to enter the market. 
We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties 
and decide whether to invest in them or not. 

The company wants to know:
-> Which variables are significant in predicting the price of a house, and
-> How well those variables describe the price of a house.


# Problem Solving Methodology :
1. Data Understanding: Understanding the data: shape, data types and statistical info
2. Data Preparation : Missing value treatment and outlier analysis
3. Data Exploration : EDA Univariate and Bivariate analysis
4. Data Preprocessin: Transforming output variable,label encoding and creation of dummies
5. Data Modelling : Train test split,Feature scaling,RFE ,Ridge and Lasso regression
6. Conclusion : Recommending the top 10 predictor variables
  
  
 ## Conclusion :
 The variables which are significant in predicting the price of a house are :
    -LotFrontage : If the house Linear feet of street connected to property area increase then the Sales Price increase.
    -BsmtFullBath : : If the BsmtFullBath area is more the SalePrice is higher
    -Overall Condition: If the Overall Condition is Excellent the SalePrice is higher
    -CentralAir: If the CentralAir is Yes the SalePrice is higher
    -Overall quality: If the Overall Condition is Excellent the SalePrice is higher
    -MSZoning_RH : If the house is near residential area then the SalePrice is higher
    -Exterior1st_CBlock : IF the house Exterior1st is CBlock then price is less.


These variable coefficients tells how well they describe the price of the house. 
