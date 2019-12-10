
# Module 4 Project-  Top 5 Zipcode for Investment


## Introduction

This project's topic is to pick top 5 zipdoes from the United States to invest in.

## Data

In order to find out best area/zipcode, dataset from Zillow.com was used. Zillow is one of the well known websites for selling/buying, and renting properties in the US. Dataset contains sales price data from 1996 to 2018. 

## Business Model

Business model is inflation hedge investment which means profit over time. Investers/stake holders will buy  properties, rent, and sell them after five years for increased house value over time. 


## Assumptions

1. Buying with 100% cash
2. Properties are all fixed and renovated for next 5 years.
3. Properties will not have any vacancy periods.
4. Data from 2008 - 2018.


## Approach

Data imported and cleaned to remove or replace missing values and outliers
Data for Top 5 Markets (Dallas-For Worth, Brooklyn, Raleigh-Durham, Orlando, Nashville) extracted based on the following:
Highest ROI over period 2008 to 2018 (post housing crash and Great Recession)
Coefficient of Variation below 0.5 for zip codes selected
Top 5 zip codes in each market selected
Brooklyn and Orlando had no zip codes that met the selection criteria
Separate model for Each zip code built using Facebook Prophet
Facebook Prophet predictions used to calculate percentage growth from 2018-2023
Top 5 zip codes selected based on higest percentage growth and model performance based on root mean squared error.


## Methods

Listed methods were used to come up with the conclusions.

-Time Series Analysis
-AutoCorrelation Funcion(ACF) and Partial AutoCorrelation Function(PACF)
-Dicky-Fuller Test
-Rolling mean and rolling standare deviation
-ARIMA modeling
-One-step and dynamic forecasts


## Files

- Mod4_Final_Project : Jupyter notebook with python coding
- Mod4_presentation.pdf: PDF file with presentation slides
- Presentation.txt: Text file with recorded presentation video on Youtube.com
- Blog.txt:Text file containing address for blog posting related to this topic