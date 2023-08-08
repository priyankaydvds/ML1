# BikeSharing Case Study

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free

## Table of Contents
Linear regression assuptions: 
    1. Linear relationship between X and Y
    2. Error terms are normally distributed (not X, Y)
    3. Error terms are independent of each other
    4. Error terms have constant variance (homoscedasticity)
Steps Involved:
- Reading the data
- Data visualization
- Data Preperation
- Test-train split
- Building Linear Model
- Residual analysis
- Making Predictions
- Model evaluation


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement: BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing
 quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
 - Essentially, the company wants to know—

   1 ) Which variables are significant in predicting the demand for shared bikes.

   2 ) How well those variables describe the bike demands
- Dataset Used: day.csv 
- Data Dictionary referred 
  day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered


## Conclusions
- Overall difference between y_expected vs y_predeicted i.e 
Mean_Squared_Error : 0.012  which is close to zero.


## Technologies Used
- library - numpy,pandas,matplotlib,sklearn,seaborn,statsmodels


## Contact
Created by [@priyankaydvds] - feel free to contact me!


