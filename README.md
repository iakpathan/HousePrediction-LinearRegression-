# HousePrediction-LinearRegression-
🏡 House Price Prediction with Linear Regression
📌 Overview
```
This project uses Linear Regression to predict house prices based on key features such as area, bedrooms, bathrooms, and amenities. It applies feature engineering, scaling, and model evaluation techniques to optimize accuracy.
```
###Dataset:House Price Prediction - Kaggle
```
##installing requirements
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score,mean_absolute_error,mean_squared_error
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler,StandardScaler
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import OrdinalEncoder
```
###Evaluation:
```
1. R² (R-squared)
Definition: R², also known as the coefficient of determination, is a statistical measure that indicates how well the independent variables (predictors) explain the variance in the dependent variable (target).
2. MAE (Mean Absolute Error)
Definition: MAE is the average of the absolute errors between the predicted and actual values. It measures the magnitude of error without considering their direction (whether over or under prediction).
3.  RMSE (Root Mean Squared Error)
Definition: RMSE is similar to MAE but penalizes larger errors more heavily. It calculates the square root of the average squared differences between the predicted and actual values.
```
Conclusion: Ive got only 0.65 r2_score , yet it can be still improved ....
