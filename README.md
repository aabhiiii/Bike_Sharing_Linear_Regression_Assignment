# Bike Sharing Linear Regression Assignment
> We are trying to determine the features that helps in identifying demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. .


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this case study we are provided with the data of demand of bikes per day for 2018 and 2019
- A lot of features regarding the demand of thee bikes and other aspects are provided as a dataset.
- The dataset is about the past demands of the bikes, so it included the information of past users for bookbikes and various factors like temperature, feel like temperature,	humidity,	windspeed, holiday, weekday, workingday etc for that perticular day.
- Our objective is to find what all features/variables which are relevent in deciding the demand of the bikes and fit a linear regression model to predict future demand of the bikes.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We have got good R- Square value of 0.81 for test data which is similar to training data
- Residuals are normally distribured and variance of the residuals is constant across predictions
- VIF of all the predictors are below 5
- p-values are less than 0.05

## Recommendations
- Below are the list of important predictors and interpretaion using their coefficient value
- temp - Demand has increased when temerature increases
- windspeed - Demand has decreased when windspeed decreases
- yr - 2019 has more demand of these bikes than 2018. So demand will increase if situation becomes normal
- spring - Demand has decreased in spring season. So comany can focus to improve demand in spring
- Mist - Demand has decreased in Mist weather.
- winter - Demand has increased in winter season
- Jul - Demand has decreased in Jul month.
- Sep - Demand has increased in sept month
- Sun - On sundays we see less demand for bikes
- LightSnow - Demand has decreased in LightSnow/Light Rain weather.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.13
- Pandas - version 1.3.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.2
- statsmodels - version 0.10.2
- sklearn
- Google Colab

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the A US bike-sharing provider BoomBikes
- This project was based on the Linear Regression module in ML EPGP program in Upgrad


## Contact
Created by [@aabhiiii]- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->