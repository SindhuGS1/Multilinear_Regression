# Project Name
Boom Bikes Sharing Assignment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to ongoin Covid-19 pandemic. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes?
How well those variables describe the bike demands?
We are required to model the demand for shared bikes with the available independent variables. It will be used by the business to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
We have developed this case study as part of the Linear Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
We have used day.csv as dataframe



## Conclusions
The top 3 features contributing significantly towards explaining the demand of shared bikes are-

temp with the coefficient of 0.4728
weathersit_Light Snow/Rain (weathersit = 3) with the coefficient of −0.2864
year (yr) with a coefficient of 0.2342

## Interpretation and Suggestions-
Demand is more during Summer months(higher temperature) and clear weather conditions. So, we can do more promotions during this period.
The demand has significantly increased in the year 2019 as compared to 2018 as people must have become more aware towards conserving environment and shared bikes rentals is one of the ways to conserve it.
During spring, and light snow/rain/misty weather conditions the demand goes down as we can see that there is a negative correlation with these variables. Business can provide some offers and discounts during this time to increase the demand.



## Technologies Used
- pandas library
- numpy library
- matplotlib library 
- seaborn library
- statsmodels
- sklearn



## Acknowledgements
This project was based on Linear Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.

## Contributors
Sindhushree G S

