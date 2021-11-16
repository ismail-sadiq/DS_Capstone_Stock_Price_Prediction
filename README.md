# Stock Price Prediction Machine Learning 📉💰💵💸

## Capstone Project for Data Science Immersive Course by Misk Academy.

## Ismail Sadiq

## 14/11/2021



# Overview

Here I would like to share my capstone project idea and why I am doing it.

I would like by this topic is to use the revolution of the data science and machine learning to predict the future performance or price of a stock. I used the past 11 years' dataset of the AAPL (Apple stock) from Yahoo finance data to predict the future performance or price of the Apple company. I started my project by understanding the data with EDA and some data visualization. That gave me a strong insight into the data that I am working on. 

Machine Learning cannot in fact predict future performance or price with %100 accuracy. However, Machine Learning is still a tool that can predict future performance or price, and many people worldwide use it. ML Stock Prediction would be very useful if we mixed it with external internal management and finance tools. ML Stock Prediction might give some insight to the investor if they use it with some experience. This topic is very hot worldwide these days, especially since we are in the ear of AI and Data Science.

In my capstone project, I used the most popular packages to predict stock future performance or price, such as AutoTS, Facebook Prophet Model, and Linear Regression. My end goal is to show that the Machine Learning could be a useful tool to predict a future stock price. 



# Dataset Description

In my capstone project I used AAPL (Apple stock) data from Finance Yahoo. I used about 12 years of AAPL (Apple stock) dataset.

The linke of the dataset: https://finance.yahoo.com/quote/AAPL/history?period1=1262304000&period2=1636416000&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true

## The dataset contains the following variables:

Date: The particular date of trade-off

Open: The opening price is the price at which a security first trades upon the opening of an exchange on a trading day.

High: A record high is the highest price or amount ever reached by a security, commodity, or index on a trading day.

Low: A record low is the lowest price or amount ever reached by a security, commodity, or index on a trading day.

Close: The closing price is the raw price or cash value of the last transacted price in a security before the market officially closes for normal trading.

Adj Close: The adjusted closing price amends a stock's closing price to reflect that stock's value after accounting for any corporate actions.

Volume: Stock trading volume would refer to the number of shares of a security traded between its daily open and close.

# Apple Stock Price Analysis

<img width="918" alt="Apple Stock Price Analysis" src="https://user-images.githubusercontent.com/89701837/141690794-e3248225-b3a0-4db5-ab06-ddaffa43ec16.png">


# Analytic Approach

### Linear Regression

It is an algorithm of supervised machine learning in which the predicted output is continuous with having a constant slope. It is used to predict the values in a continuous range instead of classifying the values in the categories. Linear regression is used for performing different tasks like house price prediction

### AutoTS Package

It is an open-source python library basically used to automate Time Series Forecasting. It will automatically train multiple time series models using a single line of code, which will help us to choose the best one for our problem statement.

### Facebook Prophet Model

Prophet is an open-source software released by Facebook’s Core Data Science team. Prophet is a forecasting procedure implemented in R and Python. It is fast and provides completely automated forecasts that can be tuned by hand by data scientists and analysts.

# APPL Future Price

![APPL Future Price](https://user-images.githubusercontent.com/89701837/141690741-73a5b22d-375f-49e8-9d26-bc0bf17d2742.png)

# Future work 
In the future, I would expand more to this project by using more advanced tools and algorithms such as :
- Moving Average
- Long Short Term Memory (LSTM)
- k-Nearest Neighbours
- ARIMA Model
- Seasonality Time Series Analysis

# Conclusion 


By using 3 machine learning methods on Apple stock, our analysis shows that Apple stock is still a valuable investment for the future. However, Value investors need to conduct an external-internal business analysis to develop the full picture of the company's future value before the investment decision.
