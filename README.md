# Kaggle Challenge: Walmart stores sales forecasting
This repository presents a bunch of notebooks to tackle Kaggle Challenge i.e. Walmart Store sales forecasting. 

## Dataset
Dataset is available at:
https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting

It consists of total 45 stores sales consisting of different products at different timestamps. 

## Approches
As it is a time series dataset, different forecasting algorithms were tried as presented in the notebooks. Forecasting algorithms are:
1. Linear Regression
2. Fb Prophet
3. LSTM (keras)
4. LSTM (Pytorch)
For dimensionality reduction, auto-encoders were trained both in Keras and Pytorch.

## Results
Forecasting result of FP prophet model is:
<p align="center"><img src="fb_prophet result.PNG"></p>

Comparison of different models and approaches as compared to 1st ranked solution:
<p align="center"><img src="rmse comparisons.PNG"></p>

