# Rossmann_Store_Sales

# Problem Statement
To predict sales for all the stores and the no of customers visiting the store,Analyze the impact on sales due to various factors such as holidays and competitor's store’s distances. and Analyze the impact on sales based on the promotions offered by the stores.

# Description
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality.

With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

# Dataset
View and download the data here: https://www.kaggle.com/c/rossmann-store-sales/data

# Approach
XGBRegressor has been used as the Gradient Boosting Machine along with K fold cross validation and hyperparameters to reduce overfitting.
A public score of 0.13042 has been achieved on Kaggle.
