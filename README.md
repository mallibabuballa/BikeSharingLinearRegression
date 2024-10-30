# Project Name: bike-sharing rental demand prediction model case study
> Project Description:
BoomBikes, a US bike-sharing provider, has seen a significant drop in revenue due to the COVID-19 pandemic and is struggling to sustain its operations. To recover post-lockdown, the company aims to understand the demand for shared bikes in the American market. They have engaged a consulting firm to identify key factors influencing bike demand and assess how well these factors predict demand. A large dataset on daily bike usage, incorporating various demographic and meteorological factors, has been collected to aid this analysis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General Information about the Project
This project aims to build a multiple linear regression model to predict the demand for shared bikes using a dataset that includes various independent variables. The model will help BoomBikes, a bike-sharing service provider, understand how different factors influence bike rental demand and enable the company to formulate effective business strategies in a post-pandemic environment.

- Background of the Project
The COVID-19 pandemic has significantly impacted various industries, including bike-sharing services. BoomBikes has experienced a decline in revenues and is seeking to adapt to changing consumer behavior as the economy recovers. Understanding the demand dynamics for shared bikes is crucial for developing a business plan that caters to customer needs and improves revenue streams. This project leverages a dataset containing historical bike rental data, alongside meteorological and demographic variables, to analyze demand patterns.

- Business Problem the Project is Trying to Solve
The primary business problem addressed by this project is the uncertainty surrounding bike rental demand in a post-pandemic context. BoomBikes needs to identify key factors that influence bike demand, assess the significance of these factors, and predict future demand to optimize operations and marketing strategies. The insights gained will help BoomBikes position itself competitively in the market, ensuring that they can meet customer expectations and capitalize on the anticipated recovery in bike-sharing usage.

- Dataset Being Used
The dataset utilized in this project contains daily bike rental records across the American market, capturing various factors influencing demand. Key columns include:

cnt: Total number of bike rentals (target variable).
casual: Number of casual users who made a rental.
registered: Total number of registered users who made a booking.
weathersit: Categorical variable indicating the weather situation.
season: Categorical variable representing different seasons.
yr: Indicator for the year (0 for 2018 and 1 for 2019).
Additional variables may include temperature, humidity, and other meteorological data that could impact bike usage. The project will involve data cleaning, transformation (e.g., converting numerical categories to categorical strings), and feature selection to build an effective predictive model.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion categorical columns as below:
 Season Variable: Fall season has more bookings and then followed by summer.
 Month Variable: Bookings are more in the month of may, june, july, aug, sep and oct and increasing trend.
 Weathersit variable: Clear weather attracted more rental bookings.
 Weekday variable: Thu, Fir, Sat and Sun have a greater number of bookings as compared to the start of the week.
 Holiday variable: Average number of bookings are comparatively less during holidays
 Working day variable: Booking seemed to be almost equal either on working day or non-working day.
 Year Variable: 2019 attracted a greater number of booking from the previous year

- Conclusion top 3 features which help 
Temperature (temp): Coefficient: 0.531651 P-Value: 9.83e-86
Year (yr):Coefficient: 0.229323 P-Value: 2.52e-107
Weather Situation (weathersit_Light_snowrain): Coefficient: -0.247816 P-Value: 9.07e-20
These features have both low p-values and substantial coefficients, indicating their strong influence on bike demand.


## Technologies Used
- NumPy package version: 1.24.3
- Pandas package version: 2.0.3
- Seaborn package version: 0.12.2
- matplotlib pacakge Version: 3.7.2
- Python version: 3.11.5
- sklearn.preprocessing
- statsmodels.api
- sklearn.feature_selection
- sklearn.linear_model

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upgrad as part of Linear regression case study
- References: sessions from upgrad and learning content from upgrad portal and internet 

## Contact
Created by Mallibabu Balla
