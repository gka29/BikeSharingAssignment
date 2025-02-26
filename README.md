# Project Name - Bike Sharing Assignment
> In this assignment, we are required to model the demand for shared bikes with the available independent variables using a multi linear regression method. Also, this will help business to understand which variables are significant in predicting the demand for shared bikes. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Python Libraries](#python-libraries)
* [Conclusions](#conculsions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- Bike sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental and return back has become      automatic. You can rent bike from one station and return this bike any of the other station all process is online. Through these systems, the user    is able to easily rent a bike from a particular position and return back at another position. There is a huge data for research generated by the      bike sharing system. which can be very useful in many cases. 
- Attribute information 
    - instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
    - weathersit : 
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

- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- Business problem is the considerable dips in their revenues due to the ongoing Corona pandemic. So Problem solving agenda is to find the features (independent variables) which are significantly increase the demand for shared bikes. So management can use this to understand and manipulate the business strategy to meet the demand and customer expectations. 

- Task performed 
- Step 1: Reading and Understanding the Data
- Step 2: Data Preparation & Visualising the Data
- Step 3: Splitting the Data into Training and Testing Sets
- Step 4: Building a linear model
- Step 5: Refine the model (if required)
- Step 6: Residual Analysis and Making Predictions Using the Final Model
- Step 7: Model Evaluation
- Step 8: Business Model Equation

## Technologies Used
- Python - version 3.12.4

## Python Libraries: 
- Pandas , Numpy , Matplotlib , Seaborn , sklearn , statsmodels

## Conclusions

- Temperature (temp) has the strongest positive impact.
- Humidity (hum) and Windspeed (windspeed) negatively impact rentals: which means Higher humidity and wind speed reduce bike demand
- Season and Weather Conditions Matter: Spring (season_1) reduces rentals (-1073), but Fall (season_3) increases them (+684). Clear weather (weathersit_1) has a strong negative impact (-2011 rentals).
- Month-wise trends: November (mnth_11) increases rentals (+501), while months like April (mnth_4), May (mnth_5), and September (mnth_9) show declines.

## Acknowledgements
This project was inspired by UpGrad IITB Programme as an assignment for the Machine Learning and Artificial Intelligence course.
Special thanks to the team for providing the resources and support for this case study.

I also referred [Machine Learning 101](https://www.udemy.com/course/machine-learning-101-with-scikit-learn-and-stats-models/) 

## Contact
[Girish Kumar](https://github.com/ga898) - feel free to contact me!
