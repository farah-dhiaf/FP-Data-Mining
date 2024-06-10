# FP-Data-Mining

|Nama Anggota |NRP |
|---|---|
|Farah Dhia Fadhila | 5025211030 |
|Salsabila Fatma Aripa | 5025211057|
|Katarina Inezita | 5025211148|
|Alfa Fakhur Rizal Zaini |5025211214|

Prediction of Flood Probability using regression and ensemble method. The dataset used is from Kaggle Competition (https://www.kaggle.com/competitions/playground-series-s4e5) and the goal is to predict the probability of a region flooding based on various factors. 

There are 4 scenarios:
1. Scenario 1: Remove outliers + Standard Scaler
2. Scenario 2: Remove outliers + MinMax Scaler
3. Scenario 3: No remove outliers + Standar Scaler
4. Scenario 4: No remove outliers + MinMax Scaler

Those scenarios will be implemented into 4 regression method:
1. Linear Regression
2. Logistic Regression
3. XGBoost
4. Light GBM

The models will be evaluated based on MSE, RMSE, and R2.