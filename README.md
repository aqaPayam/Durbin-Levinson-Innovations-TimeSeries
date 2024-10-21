
# Time Series Forecasting with Durbin-Levinson and Innovations Algorithms

**Name**: Payam Taebi  
**Course**: Time Series  
**Instructor**: Dr. Fotouhi  

This repository contains a Jupyter notebook that delves into advanced time series forecasting techniques, focusing specifically on the **Durbin-Levinson Algorithm** and the **Innovations Algorithm**. The notebook demonstrates both the theory and practical implementation of these algorithms, using Python, for forecasting time series data.

## Table of Contents

- [Introduction](#introduction)
- [Notebook Overview](#notebook-overview)
- [Key Concepts](#key-concepts)
- [Objectives](#objectives)
- [Conclusion](#conclusion)

## Introduction

This notebook is aimed at readers with prior knowledge of time series forecasting techniques such as **stationarity**, **autocorrelation**, and models like **ARIMA**. Instead of covering introductory topics, it focuses on advanced algorithms—**Durbin-Levinson** and **Innovations**—and how to implement them in Python for accurate and reliable forecasting.

You will also explore the differences between the `forecast`, `get_forecast`, `prediction`, and `get_prediction` functions, and learn when and how to use them in time series analysis.

## Notebook Overview

1. **Durbin-Levinson Algorithm**:
   - The **Durbin-Levinson Algorithm** is a recursive method used to estimate parameters in autoregressive processes. It is particularly useful when dealing with stationary time series data.
   - This section walks through the theoretical foundation of the algorithm and provides practical implementations using Python, showing how it can be used to forecast future values based on past observations.

2. **Innovations Algorithm**:
   - The **Innovations Algorithm** is a method used in time series analysis to model and predict future values. Unlike the Durbin-Levinson Algorithm, it can handle non-stationary time series or series with complex patterns.
   - This section explains the algorithm step-by-step and demonstrates how to use it in Python for effective time series forecasting.

3. **Practical Python Implementations**:
   - This section focuses on using Python's time series forecasting libraries and functions, including `forecast`, `get_forecast`, `prediction`, and `get_prediction`.
   - You will learn:
     - The distinction between **forecasting** and **prediction**.
     - How to apply these functions to make accurate forecasts from time series data.
     - The appropriate scenarios for each function and how to interpret the results.

## Key Concepts

The key focus of this notebook is on advanced time series forecasting algorithms and their practical application:

- **Durbin-Levinson Algorithm**: A recursive method used for autoregressive processes, crucial for accurate parameter estimation and time series forecasting.
  
- **Innovations Algorithm**: A powerful tool for predicting time series data, particularly for non-stationary or complex series.

- **Forecast vs. Prediction**: Clarifying the differences between these two terms, and demonstrating when and how to use each in practice, especially when using Python functions like `get_forecast` and `get_prediction`.

## Objectives

By the end of this notebook, you will have:

- A deep understanding of the **Durbin-Levinson Algorithm** and its application in time series forecasting.
- The ability to implement the **Innovations Algorithm** to handle complex time series data.
- A clear understanding of the **forecast** and **prediction** functions in Python, and how to use them effectively in time series analysis.

## Conclusion

This notebook is designed for practitioners looking to expand their knowledge of time series forecasting with more advanced methods. Through the implementation of the Durbin-Levinson and Innovations algorithms, you will be able to forecast time series data with increased precision. The Python examples provide a practical, hands-on guide to applying these algorithms in real-world scenarios.
