# Stock-Portfolio-Optimization
This repository contains a Jupyter Notebook that implements stock portfolio optimization techniques. The goal of portfolio optimization is to help investors allocate capital in a way that maximizes return while minimizing risk, based on historical stock data.

## Introduction
This project demonstrates how to optimize a stock portfolio using mathematical and statistical models. Portfolio optimization seeks to allocate assets in such a way that maximizes returns for a given level of risk or minimizes risk for a given level of return. The techniques implemented here include:

**Markowitz Mean-Variance Optimization<br>
Sharpe Ratio Maximization<br>
Risk-Parity Portfolio<br>**

## Dataset
The project requires a dataset containing historical stock price data, such as daily closing prices of several stocks over a specified time period. The dataset is obtained from financial sources such as Yahoo Finance APIs.

The dataset used in this notebook includes: 
Tickers of several stocks and their daily historical price data(Closing Price, Adj Closing Price, and more.)

## Methods Used
The following portfolio optimization techniques are implemented:

**1. Mean-Variance Optimization (Markowitz Model):** Minimizes portfolio variance given expected returns.
**2. Sharpe Ratio Maximization:** Maximizes risk-adjusted returns.
**3. Risk Parity Portfolio:** Allocates capital to equalize risk contributions from all assets.
Key metrics calculated in the notebook include:
- Expected returns
- Portfolio variance
- Covariance matrix of stock returns
- Sharpe ratio
- Efficient frontier visualization

## Results
The notebook provides the following results:

- Optimal portfolio weights for minimizing risk or maximizing return.
- Visualization of the efficient frontier.
- Portfolio metrics such as expected return, volatility, and Sharpe ratio.
