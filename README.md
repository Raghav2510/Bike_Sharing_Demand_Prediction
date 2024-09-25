# Project Name
> Bike Sharing Assignment 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- to build a multiple linear regression model for the prediction of demand for shared bikes.
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
  Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, 
  and the system unlocks it. 
  This bike can then be returned to another dock belonging to the same system.
  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
  The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business 
  plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
  
  In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends
  across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better 
  all around and stand out from other service providers and make huge profits.
  They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. 
  Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

   Which variables are significant in predicting the demand for shared bikes.
   How well those variables describe the bike demands
   Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

- Required to model the demand for shared bikes with the available independent variables. It will be used by the management to 
  understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet 
  the demand levels and meet the customer's expectations. 
  Further, the model will be a good way for management to understand the demand dynamics of a new market.
- Using days.csv dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Based on the final model, below are the top 3 features contributing significantly towards explaining the demand of the shared bikes.	(2 marks)
sat :- A coefficient value of 0.0698 indicates that a unit increase in temp variable increases the bike hire numbers by 0.0698 units.
yr:- A coefficient value of 0.241 indicates that a unit increase in yr variable increases the bike hire numbers by 0.241 units.
light snow & rain:- A coefficient value of -0.3096 indicates, a unit increase variable decreases the bike hire numbers by 0.3096 units.




## Technologies Used
- Python - version 3.10.8
- Pandas - version 2.2.1
- numpy - version 1.26.4
- Matplotlib - version 3.8.3
- seaborn - version 0.13.2
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is developed as an case study assignment for IIIT, Bangalore.
