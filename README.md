# Advanced Regression Assignment
## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

### Technologies Used
* IPython - Version 7.29.0
* Pandas - Version 1.3.4
* NumPy - Version 1.20.3
* Jupyter Notebooks - Version 6.4.5
* Seaborn - Version 0.11.2
* Matplotlib - Version 3.4.3
* Scikit - Version 0.24.2
* StatsModel Api - Version 0.12.2

## Observations and Conclusions
Since the R2 score for Lasso Model is comparatively higher than Ridge Model, the choice of model for this use case is Lasso Regression Model.
Top 5 important predictors based on the mod value for both Ridge and Lasso models are 'LotArea', 'OverallCond', '2ndFlrSF', 'KitchenQual' and 'BsmtQual'.
The next 5 most import predictor variables of the Lasso model are - 'OverallQual', 'Functional_Mod', 'MSZoning_RL', 'GarageType_Basment' and 'MSZoning_RH'
