# BoomBikes 
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

> Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Table of Contents
* General Information 
* Technologies Used: Python-statisticsModel and sklearn 
* Conclusions
* Acknowledgements


## General Information
- We have created a multiple regression model to predict the number of bikes to be rented when the pandamic ends given the various meteorological conditions, and people's style of renting a bike.
Provide general information about your project here.
- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- The dataset day.csv is given to us for this assignment. It has 730 records and 16 features. There is 1 object type, 4 float and 11 int type features. There are no missing values in the dataset.



## Conclusions
- The Regression model produced follows all the assumptions of a theoretical Regression model
- The R-squared is 85% 
- All the features have VIF less than 5. 
- The top 5 features suggested in this model are: Temp, Windspeed, Humidity, Light Snow as Weather situation, Year



## Technologies Used
- Python 3.8.5



## Acknowledgements
- This Project is a part of Upgrad ML assignment
- The github link to this project is git@github.com:seemasim/RentalBike_assignment.git


## Contact
Created by [@seemasim] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->