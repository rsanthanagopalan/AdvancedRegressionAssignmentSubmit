# AdvancedRegressionAssignmentSubmit
Submission for an advanced regression case study on housing datasets
> Problem Statement:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. 

The company wants to know:

1) Which variables are significant in predicting the price of a house, and
2) How well those variables describe the price of a house.

## Table of Contents
* [General Info](#general-information) 
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> Goal: 
Model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
> Analysis: 
- Ridge {'alpha': 100}
- Lasso {'alpha': 0.001}
- Base model features of significance determined using the values of coefficients sorted in descending sequence (ranked most important & below),
- **Features Ridge**
  - GrLivArea 
  - 1stFlrSF  
  - TotalBsmtSF  
  - LotArea  
  - BsmtFinSF 
  - 2ndFlrSF  
  - GarageArea  
  - OverallQual_8  
  - OverallQual_9  
-   **Features Lasso**
    - GrLivArea  
    - TotalBsmtSF  
    - LotArea  
    - BsmtFinSF1  
    - OverallQual_9  
    - OverallQual_8  
    - GarageArea  
    - Neighborhood_Crawfor  
    - OverallCond_8  
    - OverallCond_7  
    - Exterior1st_BrkFace  
    - BsmtExposure_Gd  
    - OverallCond_9  

## Technologies Used
- Pandas
- Numpy
- Seaborn
- Matplotlib
- SKLearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upGrad course in Linear Regression
- This project was based on [Advanced Regression](https://www.upgrad.com).


## Contact
Created by [@rsanthanagopalan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
