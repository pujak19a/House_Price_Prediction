# Housing Price Prediction (Advanced Regression Assignment)
# Prediction of House Price
> This Assignment is about finding the important features which impacts the Sales Price of House, also about creating model for Price Prediction.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
#### Background
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

#### Business Goal:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

#### Steps for Model Building
1.Reading and Understanding Data
2.Visualising the Data
3.Data Preparation
4.Splitting the Data into Training and Testing Sets
5.Feature Scaling
6.Building the Model
7.Residual Analysis of the train data
8.Making predictions using final model
9.Model Evaluation

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Ridge regression is giving better results 
- most important features are 
OverallQual 0.133
GrLivArea 0.108
1stFlrSF 0.097
2ndFlrSF 0.072
GarageCars 0.067
MasVnrArea 0.066
RoofMatl 0.061
TotRmsAbvGrd 0.058
LotArea 0.049
OverallCond 0.046
BsmtFinSF1 0.038

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy- version 1.24.3
- pandas- version 1.5.3
- matplotlib- version 3.7.1
- seaborn- version 0.12.2
- statsmodels- version 0.13.5
- sklearn - 1.2.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by [@pujak19a] - feel free to contact me!


