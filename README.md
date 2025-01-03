# Dominos - Predictive Purchase Order System

## Project Overview
Dominos wants to optimize the process of ordering ingredients by predicting future sales and creating a purchase order. By accurately forecasting sales, Dominos can ensure that it has the right amount of ingredients in stock, minimizing waste and preventing stockouts. This project leverages historical sales data and ingredient information to develop a predictive model and generate an efficient purchase order system.

## Skills Learned
- **Data Cleaning and Preprocessing**: Handling missing data, outlier detection, and normalization.
- **Exploratory Data Analysis (EDA)**: Analyzing trends, seasonality, and other patterns in the dataset.
- **Time Series Forecasting**: Using time series models to predict future sales.
- **Predictive Modeling**: Building and evaluating models to make predictions.
- **Business Decision Making**: Translating model outputs into actionable insights for business operations.
- **Real-World Application of Data Science**: Applying machine learning techniques to solve real-world problems.

## Domain
- **Industry**: Food Service Industry
- **Company**: Dominos

## Objective
The project aims to predict future ingredient requirements by forecasting sales data. By predicting the sales, Dominos can generate an optimized purchase order to minimize waste and prevent stockouts.

## Approach

1. **Data Preprocessing**: 
   - Cleaned and preprocessed the historical sales data.
   - Handled missing values, outliers, and other inconsistencies.

2. **Exploratory Data Analysis (EDA)**: 
   - Performed EDA to analyze trends, seasonality, and other key patterns in the data.

3. **Modeling**:
   - Built time series forecasting models to predict future sales and ingredient requirements:
     - **ARIMA (AutoRegressive Integrated Moving Average)**
     - **SARIMAX (Seasonal AutoRegressive Integrated Moving Average with Exogenous Regressors)**
     - **Prophet (by Facebook)**

4. **Model Evaluation**:
   - Evaluated the models based on Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Models Used
- **ARIMA**: ARIMA is the best-performing model for forecasting.
- **SARIMAX**: Seasonal variant of ARIMA, which performed well but not as efficiently as ARIMA.
- **Prophet**: A forecasting tool by Facebook, which also provided good results but not as accurate as ARIMA.

### Model Performance:
- **ARIMA**:
  - MAE: 1.8164
  - MSE: 5.4466
  - RMSE: 2.3338
  
- **SARIMAX**:
  - MAE: 2.5756
  - MSE: 8.2964
  - RMSE: 2.8803
  
- **Prophet**:
  - MAE: 2.7042
  - MSE: 8.5594
  - RMSE: 2.9256

### Best Model: ARIMA

## Results
The **ARIMA model** provided the best performance in terms of MAE, MSE, and RMSE. The model is used to generate the purchase order, predicting ingredient quantities for future periods to ensure efficient stock management.

