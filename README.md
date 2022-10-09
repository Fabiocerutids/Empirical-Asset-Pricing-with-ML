# Empirical-Asset-Pricing-with-ML
The repository contains an analysis employing different ML tools with the goal of generating a portfolio capable of beating the market over a test window of 540 days.
The analysis is composed by the following steps:

1) Data exploration and descriptive statistics
2) Generating training and test samples and comparing predictive performance out of sample of a linear model and a ridge regression both with 1 lag
3) Identifying the optimal number of lags to include in the regression
4) Evaluating the performance of various non linear models (XGBoost, SVM, MLPR, Bi-LSTM)
5) Evaluating the performance of the AI portfolio vs the S&P500 and 1000 randomly generated portfolios
6) Evaluating the performance of the AI portfolio vs the S&P500 when transaction fees are present on each transaction
