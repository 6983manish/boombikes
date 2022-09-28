# BoomBikes 
> Build a multiple linear regression model for the prediction of demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Problem Statement: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands
3. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

- What is the business probem that your project is trying to solve?
ANS: We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- What is the dataset that is being used?
ANS:
- [day.csv](https://github.com/6983manish/boombikes/blob/7a4e1bf96068f640e8db5077ab166787e52ca7b1/day.csv)
- https://github.com/6983manish/boombikes/blob/7a4e1bf96068f640e8db5077ab166787e52ca7b1/datadictionary.txt


## Conclusions
- The months of August September and October and the season of Summer is when the demands are at the best.
- The bookings by registered users are high during weekdays while casual users book high during weekdays, Higher number of bookings are done on weekdays than the weekends
- Sundays have the least bookings. There is a gradual increase in bookings as the week progresses until Thursday and then it goes down
- Casual books have a reverse trend to total bookings. The bookings are high on Sunday and gradually reduce during the weekdays until Thursday and subsequently increase.

## Technologies Used
- Python 3
- Library - Seaborn, Numpy, Matplotlib, Pandas, Sklearn and StatsModels
- Git & Github for version control and file hosting

## Contact
Created by @6983manish 
