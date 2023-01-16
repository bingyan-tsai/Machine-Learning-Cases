# Machine-Learning-Cases
created by Jason Tsai from National Yang Ming Chiao Tung University, Taiwan.

## Introduction
This repository contains various management problems which we want to solve through machine learning. The open-source IDE Jupyter notebook is used to perform our code and results. 

## Employee Attrition Prediction
In Business, employee attrition is always a critical issue. In order to figure out key factors that impact employees' intention of quitting, various models are introduced (like Ada Boost, SVM Classifier, Back Propagation .etc) in this case. In the end, we found out that Random Forest Classifier has the best performance no matter in terms of ACC or using Area Under Curve for evaluation. On the other hand, salary, frequency to shift, and work hours are the key factors that influence employees' decision of leaving.

## PM2.5 Concentration Prediction
In this case, we try a simple Linear Regression and XGBoost to forecast the daily PM2.5 concentration in Hsinchu County, Taiwan. The result implies that XGBoost seems like easily to fall into the problem of "Overfitting." On the other hand, a simple Linear Regression performs better on PM2.5 prediction in terms of MAE and MSE.

## Sentiment Analysis of Restaurant Reviews
We use Keras to construct CNN and LSTM models to identify the sentiment of restaurant reviews. Before classification, the text tokenizer provided by Keras is used for data pre-processing in this case. Also, we use a dropout layer to avoid overfitting, and the 'sigmoid' function is used as an activation function.

## Environment
```
Python 3.9.12
```

## Installation
```
numpy
pandas
sklearn
matplotlib
```
