# Quarterly Alcohol Consumption Analysis

## Overview

This repository contains a comprehensive analysis of quarterly alcohol consumption trends spanning from the years 2000 to 2012. The investigation employs various forecasting methods, including Moving Average, Exponential Smoothing, Linear Regression, and Autoregressive Integrated Moving Average (ARIMA), to predict Quarterly Alcohol Consumption effectively and efficiently. The study aims to provide valuable insights into alcohol consumption patterns and their changes over a 12-year period.

## Table of Contents

- [Objective](#objective)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributors](#contributors)

## Objective

The primary objective of this case study is to analyze historical alcohol consumption data and apply various forecasting techniques to predict future quarterly alcohol consumption. By doing so, we aim to gain insights into consumption patterns, assess the performance of different forecasting methods, and provide valuable recommendations for decision-makers.

## Dataset

The data used in this analysis covers a 12-year span from Q1 2000 to Q4 2012. It includes quarterly distribution of alcohol consumption. The dataset is readily accessible and does not require additional processing.

## Methodology

The case study employs the following forecasting methods:

- **Moving Average:** Three different moving average periods (3, 4, and 6) are used to predict consumption.

- **Exponential Smoothing:** The technique is applied with varying alpha (α) values (0.1, 0.2, and 0.3) to capture trends and seasonality in the data.

- **Linear Regression:** A linear regression model is employed to provide insights into future consumption patterns.

- **ARIMA (Autoregressive Integrated Moving Average):** Two ARIMA models, including Dynamic Forecasting and One-Step Forecasting, are used to forecast future demand patterns.

## Results

The performance of each forecasting method is evaluated using Root Mean Square Error (RMSE) and Mean Absolute Error (MAE). Here are some key findings:

- Moving Average with a period of 4 outperformed other moving average periods with the lowest RMSE and MAE scores.

- Exponential Smoothing with alpha (α) value of 0.3 demonstrated the best performance among all Exponential Smoothing methods.

- Linear Regression provided moderate accuracy in predicting demand.

- ARIMA Dynamic Forecasting had the lowest RMSE and MAE scores, indicating high accuracy in predicting future demand patterns.

## Conclusion

Based on the analysis, the Exponential Smoothing Technique with an alpha (α) value of 0.3 performed the best in forecasting quarterly alcohol consumption. These insights can be valuable for decision-makers in understanding and managing alcohol consumption trends.

## Contributors

- Emmanuel Tadese
- Simranjeet Kaur
- Sougata Dey
- Anand Shroff
- Mazhar Noor


