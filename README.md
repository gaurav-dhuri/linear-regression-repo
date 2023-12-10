# Project Name
> Multiple Linear Regression - Shared Bike Service

## General Information
- Building a multiple linear regression model for the prediction of demand for shared bikes.

- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 

- The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business 
  plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end

- BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due 
  to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out 
  from other service providers and make huge profits.
  As a consultant they have contracted to understand the factors on which the demand for these shared bikes depends.
  The company wants to know:
   1. Which variables are significant in predicting the demand for shared bikes.
   2. How well those variables describe the bike demands

- Data Set provide is day.csv


## Conclusions
- EDA Analysis
   1. Fall season has more more bookings than any other season and has increased with increase in year aswell.
   2. Most of the bookings gradually starts rising from the begining of the year, highest bookings are observed in May, June, July, August and September
      and then gradually starts to decline.
   3. Clear weather attracts more booking than any outhet weather.
   4. For holiday demand seems to dropped, which seems reasonable, people might spend sometime with family.
   5. Year 2019 has more number of booking from the previous year, which shows good progress in terms of business.

- Final model prediction
   1. Train dataset R2 : 0.838
   2. Train dataset Adjusted R2 : 0.834
   3. Test dataset R2 : 0.803
   4. Test dataset Adjusted R2 : 0.792
   
- Feature which holds significance in contributing towards the rise in demand for share bike are as follows:
1.  Year
2.  Temp
3.  Humidity
4.  Windspeed
5.  Summer
6.  Winter
7.  September
8.  Sunday
9.  Light Snow
10. Mist

## Technologies Used
- Jupyter Notebook
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborne
- StatsModel
- SkLearn

## Contact
Created by [gaurav-dhuri] - feel free to contact me!
