# Time-Series-Modelling-Case-Study
# Oil Price Forecasting 📈

## Overview
This project explores **time series forecasting** of daily oil prices using two approaches:

- **ARIMA** – classical statistical time series model  
- **LSTM** – deep learning model for sequential data  

The goal is to analyse oil price data, build forecasting models, and compare their performance in predicting future prices.

---

## Dataset 📊

The dataset contains **daily oil price observations (2024–2026)**.

Columns:
- `date` – observation date  
- `price (dollars)` – oil price in USD  

Total observations: ~500 daily records.

---

## Workflow ⚙️

The project follows a standard time series modelling pipeline:

1. **Data Preprocessing**
   - Load dataset
   - Convert to time series format
   - Handle missing values

2. **Exploratory Data Analysis**
   - Time series visualization
   - 60-day rolling trend analysis

3. **Stationarity Testing**
   - Augmented Dickey-Fuller (ADF) test
   - Differencing if required

4. **Model Development**
   - ARIMA model with parameter search
   - LSTM neural network for sequence modelling

5. **Evaluation**
   Models are evaluated using:
   - RMSE
   - MAE

6. **Forecasting**
   Generate **24-month forecasts (~730 days)** of future oil prices.

---

## Results 📉

- **ARIMA (Walk-Forward)** produced the lowest prediction error.
- **LSTM** captured the general trend but showed slightly larger deviations.

This suggests that **statistical models can perform well on smaller datasets**, while deep learning models often benefit from larger training data.

---

## Tools Used 🧰

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- TensorFlow / Keras
- Scikit-learn

---

## Author 👨‍💻

Varun paka
