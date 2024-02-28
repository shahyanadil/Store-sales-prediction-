# Store Sales Time Series Analysis

This repository contains the code and analysis for analyzing store sales time series data.

## Introduction

In this project, we aim to perform time series analysis on store sales data to gain insights and make predictions. The analysis includes exploring various aspects of the data such as sales trends, seasonal patterns, correlations with external factors like oil prices and holidays, and building predictive models.

## Libraries Used

The analysis code utilizes several R libraries including:

- tidyverse
- magrittr
- Metrics
- plotly
- OpenStreetMap
- maps
- zeallot
- lubridate
- cowplot
- dplyr
- png
- tsibble
- fable
- fabletools
- feasts
- tsibbledata
- tibble
- tidyr
- readr
- ggplot2
- corrplot

## Data

The data used in this analysis includes various datasets related to store sales, transactions, stores information, oil prices, and holiday events. These datasets are read into R environment from CSV files.

## Exploratory Data Analysis

The exploratory data analysis includes examining the structure of the datasets, checking for missing values, summarizing sales by product family and store, visualizing sales distributions, analyzing sales trends by date, day of the week, month, and year, exploring store types and their sales distribution, and investigating the correlation between different variables.

## Holiday Events Analysis

The analysis includes examining holiday events data, categorizing holidays by locale and type, visualizing the distribution of national holidays by month, and exploring the impact of holidays on sales.

## Oil Prices Analysis

The analysis includes examining oil prices data, visualizing the fluctuation of oil prices over time, and investigating the relationship between oil prices and store sales.

## Modelling for Time Series Forecasting

Various time series forecasting models are implemented including ARIMA, Exponential Smoothing (ETS), and Seasonal Naive methods. These models are trained on historical sales data and used to forecast future sales.

## Store Sales Prediction

Separate time series forecasting models are built specifically for predicting store sales. Similar to the overall time series forecasting, models such as ARIMA, Seasonal Naive, and ETS are applied to predict future store sales.

## Conclusion

This analysis provides valuable insights into store sales data and demonstrates the effectiveness of time series forecasting models in predicting future sales. The findings can be used by stakeholders for decision-making and strategic planning.
