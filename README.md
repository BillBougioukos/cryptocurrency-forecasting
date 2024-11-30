# cryptocurrency-forecasting
A project analyzing and forecasting cryptocurrency prices using various time series methods, including Naive, Moving Average, and Exponential Smoothing.

Cryptocurrency Forecasting Project


Introduction

Cryptocurrencies represent a significant shift in the financial sector, providing a decentralized, digital alternative to traditional currencies. This project aims to analyze cryptocurrency data from 2021 and 2022, leveraging various forecasting techniques to predict future trends in cryptocurrency prices. The main objective is to develop and apply forecasting models to forecast monthly cryptocurrency values using Python.

Purpose of Analyzing Cryptocurrency Data
This project involves a thorough analysis of cleaned cryptocurrency data collected from 2021 and 2022. By applying multiple forecasting techniques, the goal is to predict the future performance of cryptocurrencies, aiding in better decision-making for stakeholders in the cryptocurrency market.

Dataset Overview
The dataset used in this project contains daily cryptocurrency price data over the course of two years: 2021 and 2022. The data is publicly available and includes metrics such as opening prices, closing prices, highest values, lowest values, and trading volume for various cryptocurrencies (e.g., Bitcoin, Ethereum).

Methodology
To forecast cryptocurrency prices, I employed the following techniques:

1. Naive Method
The Naive method uses the most recent observation as the forecast for the next period. This simple approach provides a baseline to compare the performance of more sophisticated forecasting techniques.
2. Moving Average
The Moving Average technique smooths out short-term fluctuations and highlights longer-term trends in the data. By averaging the past n observations, it gives a clearer view of the overall trend and can help predict future values.
3. Exponential Smoothing
Exponential smoothing gives more weight to recent observations, making it responsive to recent data points. This method is useful in capturing trends and making short-term forecasts.
Data Cleaning and Preprocessing
Before applying the forecasting methods, the dataset was cleaned and preprocessed to handle:

Missing data: Null values were imputed using a suitable strategy.
Outliers: Outliers were identified and addressed to improve the accuracy of the forecasts.
Date formatting: The dataset was ensured to have the correct date format and any inconsistencies were resolved.
These preprocessing steps ensured the integrity of the data before applying forecasting models.

Forecasting and Evaluation
1. Naive Method:
The forecast for each month was made using the most recent month's value, providing a simple baseline prediction.
2. Moving Average:
I implemented a moving average model with various window sizes (e.g., 7-day, 30-day) to smooth the data and identify trends. This technique allowed for better long-term predictions.
3. Exponential Smoothing:
This method was applied to capture trends more effectively by giving more weight to recent observations. The technique was fine-tuned with different smoothing parameters for optimal performance.
Model Comparison:
The three methods (Naive, Moving Average, Exponential Smoothing) were compared based on forecast accuracy using key metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
These metrics were used to evaluate and compare the performance of each forecasting model.

Results
The Moving Average model provided a balanced approach, smoothing out short-term fluctuations while tracking longer-term trends effectively.
The Exponential Smoothing model performed best in capturing recent trends, showing better responsiveness to recent price movements.
The Naive Method served as a simple baseline, but its performance was not as strong compared to the other models, which better accounted for the data's inherent patterns.
