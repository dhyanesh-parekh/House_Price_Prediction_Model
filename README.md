# Bike Sharing Demand Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Research Flow](#research-flow)
* [Acknowledgements](#acknowledgements)
* [Contributor](#contributor)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Problem
  -  **BoomBikes** wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market to regain their profits after the pandemic. The company wants to know:
      - Which variables are significant in predicting the demand for shared bikes.
      - How well those variables describe the bike demands.
- Dataset used
  - Firm's proprietary Dataset ranging from 2018-2019

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Research Flow
- Step 1 : Understanding the Data
    - Standradizing the Data
- Step 2 : Visualising the Data
    - Observations
- Step 3 : Preparing the Data
    - Creating Dummy variables for categorical features
- Step 4 : Splitting the dataframe into training and testing data
    - Scaling then training data using Min-Max Scaler
- Step 5 : Building a Linear Model
    - Automatic Feature selection using RFE
    - Building Models
- Step 6 Residual Analysis
    - Normality of Error Terms
    - Multicolinearity
    - Linearity
    - Homoscedasticity
    - Independance of Variable
- Step 7 : Making predictions using final model
    - Scaling the test data using same fitted scaler
- Step 8 : Evaluation of Model
    - Model comparison between Training and Testing dataset


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
