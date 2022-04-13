# AdvancedRegressionAssignment
## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 

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

* Temperature is the most positively contributing feature to the target variable. Summer season also has a positive relation. Hence, the company should make sure of the availability of bikes during these periods due to high demands
* Saturdays and Working days have a positive influence on the number of bookings. Also, holidays have a negative impact. Hence, the company should come up with some strategy to attract the users on Working weekdays as well as holidays.
* Weather conditions like Mist, clouds, Light Snow, Light rain etc have a negative contribution. The spring season and windy condition also can be considered as an extension to this. As such, company should come up with better or complmentary strategies to tackle this issue.
* Though the entire winter is a good contributing factor, the September month alone stands out as more contributing factor.
* There is an increase in bookings from 2018 to 2019, with an organic growth of 23%.
* Temperature with the highest positive coefficient
* Weather Situation = 3 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) has the next highest coefficient in magnitude. But the sign is negative
* Year has the third-highest effect, and it is positive
