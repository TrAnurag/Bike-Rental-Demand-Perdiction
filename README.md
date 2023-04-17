Description:
Prediction of the number of bicycles rented in an hour of a day in the Seoul Bike Sharing System based on different weather conditions and holiday information in Seoul from 1/12/2017 to 30/11/2018

Group members:
Anurag Singh Mohammad Ahmadi, Zachary Huntley

Dataset Description:
The dataset was downloaded from the https://archive-beta.ics.uci.edu/ website, which provides datasets for educational purposes. The dataset contains the number of bicycles rented per hour for each day from 1.12.2017 to 31.11.2018. The weather conditions for each hour are also specified in terms of Temperature (°C), Humidity (%), Wind speed (m/s), Visibility (10m), Dew point temperature (°C), Solar Radiation (MJ/m2), Rainfall (mm), Snowfall (cm), and Seasons. Holidays are specified for each day. As there were some days during which the Seoul Bike Sharing System was unable to provide service and no vehicle was rented, these days are shown in the Functioning Days column.

Project Summary:
Background
Seoul's bike sharing system, known as Ddareungi or Seoul Bike in English, was established in 2015 with 150 stations and 1500 bikes. Since then, the system has steadily expanded to cover new districts, and as of July 2016, there were approximately 300 stations and 3000 bikes available.

Problem Statement
One of the biggest obstacles to the success of bike sharing systems is cost. The high cost of maintaining and renewing bicycles can lead to high rental costs for customers or a large budget for municipalities, which can hinder the popularity of such an environmentally-friendly system in cities. Additionally, inaccessibility is another challenge faced by users in cities with bike sharing systems, as stations may not have enough bicycles to meet demand during certain hours, which can negatively impact the popularity of the system.

Bike sharing systems allow users to rent a bike from one station and return it to another station or simply leave it anywhere they please. In order to ensure that the system functions smoothly, providers must facilitate the relocation of abandoned bicycles to stations, which requires costly infrastructure and human resources. Predicting the number of bicycles needed can help to minimize the cost of relocations.

Furthermore, minimizing the number of bicycles stored in stations can protect the vehicles from different weather conditions and reduce maintenance costs, which can increase their lifespan and generate revenue for the system. Ultimately, accurately predicting the number of bicycles needed on an hourly basis each day can help the system balance supply and demand, leading to better service for customers.

As weather conditions play an important role in bike usage, this project surveys the forecasting of the number of bicycles needed each hour based on weather patterns.

Objective:
The objective of this project is to predict the number of bicycles that will be rented per hour for each day from 1.12.2017 to 31.11.2018 in Seoul's bike sharing system. The project aims to achieve this by analyzing the weather conditions for each hour in terms of Temperature (°C), Humidity (%), Wind speed (m/s), Visibility (10m), Dew point temperature (°C), Solar Radiation (MJ/m2), Rainfall (mm), Snowfall (cm), and Seasons. The project will use this analysis to create a model that can accurately forecast the number of bicycles needed on an hourly basis each day, helping the system balance supply and demand and provide better service to customers.

This project's ultimate goal is to minimize the number of bicycles stored in stations to reduce maintenance costs and increase their lifespan, while generating revenue for the system. Accurately predicting the number of bicycles needed can help to minimize the cost of relocations, which requires costly infrastructure and human resources. Additionally, predicting the number of bicycles needed can help to overcome the inaccessibility issue faced by users in cities with bike sharing systems, where stations may not have enough bicycles to meet demand during certain hours.

Therefore, the objective of this project is to create a predictive model that can help Seoul's bike sharing system efficiently manage its resources, leading to cost reduction and better service for customers.

Methodology:
Linear and non linear regression including Linear Regressor, Lasso Regression, Polynomial Regression used to train a model. Also ensemble methods include Random Forest Regressor, Kneighbor Regressor, Gradient Boosting Regressor, Decision Tree Regressor are tested to get the most accurate results.

Data Description:
Date : DD/MM/YYY
Rented_Bike_Count: the total number of rented bike for each hour
Hour: hour of the day
Temperature(°C): temperature measured in Celsius(°C)
Humidity(%): humidity in percent
Wind_speed(m/s): the speed of winf in m/s
Visibility_(10m): measure of the transparency of the surrounding air
Dewpoint_temperature(°C): dew point is the temperature to which air must be cooled to become saturated with water vapor in Celsius
Solar_Radiation_(MJ/m2): MJ/m2
Rainfall(mm): in millimeter
Snowfall(cm): in centimeter
Seasons: Spring, Summer, Autumn, Winter
Holiday: Holiday or No holiday
Functioning_Day: it shows that if the system were working or not. Yes or No
