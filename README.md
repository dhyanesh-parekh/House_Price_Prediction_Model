# House Price Prediction Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Research Flow](#research-flow)
* [Acknowledgements](#acknowledgements)
* [Contributor](#contributor)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Problem
  -  The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
      - Which variables are significant in predicting the price of a house.
      - How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Research Flow
- Step 1 : Understanding the Data
    - Imputing Null Values
- Step 2 : Visualizing and Dropping certain features
    - Checking the Diversity/Variance of the features
- Step 3 : Preparing the Data
    - Creating Dummy variables for categorical features
- Step 4 : Splitting the dataframe into training and testing data
    - Scaling then training data using Min-Max Scaler
- Step 5.1 : Linear Regression
    - Automatic Feature selection using RFE
    - Building Models
    - Model Evaluation
    - Residual Analysis
      - Normality of Error Terms
      - Colinearity
      - Homoscedasticity
      - Independance of Variable
- Step 5.2 : Lasso Regression
    - Setting up Hyperparameter Value
    - Building Models
    - Model Evaluation
    - Residual Analysis
      - Normality of Error Terms
      - Colinearity
      - Homoscedasticity
      - Independance of Variable
- Step 5.3 : Ridge Regression
    - Setting up Hyperparameter Value
    - Building Models
    - Model Evaluation
    - Residual Analysis
      - Normality of Error Terms
      - Homoscedasticity
      - Independance of Variable
- Step 6 : Model Comparison
    - Observation
    - Inference

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.23.5
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborne - version 0.12.2
- Scikit-learn - version 1.2.2
- Statsmodels - version 0.14.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Giving credits here.
- This project was inspired by [UpGrad](https://ww2.upgrad.com/?_gl=1*1a6yjvu*_ga*MTY4NTk0NDA2Ny4xNjk4MDg2ODEw*_ga_HVXPGHVCS0*MTY5ODA4NjgwOS4xLjAuMTY5ODA4NjgwOS42MC4wLjA.&user_uuid=478408e8-483a-4336-8184-9025c279e0af&combination_id=2) and [IIIT Banglore](https://www.iiitb.ac.in/)


## Contributor
Created by [@Dhyanesh_Parekh](https://github.com/dhyanesh-parekh) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
