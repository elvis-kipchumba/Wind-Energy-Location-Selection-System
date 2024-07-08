![image](https://github.com/Mugangasia/Capstone-Project---Predicting-Best-Location-for-Wind-Energy-in-Kenya/assets/98708792/852724e5-c4c3-4ccc-ab83-1e937e9ca7d6)

# Wind Power Plant Location Selection System

## Business Understanding 

The proposed project aims to develop a system that assists in selecting optimal locations for wind power plants based on weather conditions. The efficiency and profitability of wind energy depend on the wind patterns in specific areas. By leveraging historical weather data and geographical information, this system will provide valuable insights to energy companies and policymakers, enabling them to make informed decisions regarding the placement of wind power plants. The goal is to maximize energy generation and contribute to sustainable development by strategically locating wind power infrastructure.

The motivation behind this project is the urgent need to transition to renewable energy sources and mitigate the adverse effects of climate change caused by fossil fuel consumption. By facilitating the selection of suitable locations for wind power plants, this system can help accelerate the adoption of clean and sustainable energy solutions.

## Problem Statement 
Selecting the most suitable locations for wind power plants is crucial for maximizing energy generation and ensuring sustainable and profitable operation. The efficiency of wind energy production depends heavily on the prevailing weather conditions in specific areas. However, the lack of a comprehensive and data-driven approach to assessing the wind energy potential at different locations hinders effective decision-making for energy companies and policymakers.

This project aims to address this challenge by developing a system that leverages historical weather data and geographical information to identify and rank potential wind power plant locations in the following regions in Kenya(Kajiado, Marsabit, Laikipia,Nyeri, Meru and Samburu). Kajiado, Marsabit and Samburu already have existing power plants but the potential to produce more green power from these regions and more still exists. The biggest challenge faced by stakeholders in this industry is accurately identifying profitable wind energy-generating sites.

By creating a system that utilizes weather data and geolocation information, stakeholders can make informed choices regarding the optimal placement of wind power plants. This will result in improved energy generation efficiency, reduced reliance on fossil fuels, and a positive impact on global energy sustainability.

## Project Objectives 
* To use predictive models(LSTM and Facebook Prophet), and perform time series analysis to rank six locations based on hourly wind speed predictions.

* Develop an end product that provide insights on the suitability of setting up a turbine plant in an area.


## Success Metrics
* Prediction Accuracy: Metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE) will be used to measure the success of the predictive models.

* Minimum Viable Product (MVP): The MVP will include a baseline model that predicts wind speed in an specific location over a time difference if 1 Hour and give insights to stakeholders.

## Data Understanding
Our first dataset was collected from Kaggle from a wind power plant in Denmark. This dataset was used for our based model as it originated from actual wind turbine. 
The columns are as following;
* LV ActivePower (kW): Real-time power output of a wind turbine in kilowatts.

* Wind Speed (m/s): Speed of the wind at the turbine location in meters per second.

* Theoretical_Power_Curve (KWh): Maximum potential power output of the wind turbine at different wind speeds in kilowatt-hours.

* Wind Direction (°): Direction from which the wind is blowing at the turbine location in degrees.

* Power Loss: Losses in the wind turbine system that can affect its overall efficiency and power generation.

Our second dataset was sourced from POWER data access viewer(DAV) by NASA. It contained the date and windspeed from 2013-2023. This dataset was then used for ranking best location for power production in Kenya.

