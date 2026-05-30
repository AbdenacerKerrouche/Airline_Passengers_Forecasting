# ✈️ Air Passengers Forecasting

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Type](https://img.shields.io/badge/Time%20Series-ARIMA%2FSARIMA-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Focus](https://img.shields.io/badge/Domain-Forecasting%20%2F%20ML-blue)

---

## 📌 Overview

Time series forecasting project based on the classic **Air Passengers dataset**.

The goal is to model historical passenger demand and generate accurate forecasts by capturing **trend and seasonality patterns** using statistical time series methods.

---
## 📂 Project Structure

```bash
Images                      # Plots of the time serie in different phases in the AnaLysis
Passengers_forcating.ipynb   # Exported notebook with full analysis
README.md                   # Project documentation
```

---

## 🎯 Objectives

* Analyze historical passenger traffic data
* Identify **trend and seasonality**
* Transform data to achieve stationarity
* Build a forecasting model (ARIMA/SARIMA)
* Evaluate prediction performance

---

## ⚙️ Methodology

### 1. Data Exploration

* Visualized passenger growth over time
* Observed strong **trend and seasonal patterns**

### 2. Data Preprocessing

* Log transformation to stabilize variance
* Differencing to remove trend and seasonality
* Stationarity check using statistical tests (ADF)

### 3. Time Series Decomposition

* Trend component
* Seasonal component
* Residuals

### 4. Modeling

* Applied **ARIMA/SARIMA models**
* Tuned parameters (p, d, q) based on ACF/PACF plots

### 5. Evaluation

* Compared predicted vs actual values
* Used error metrics such as:

  * Mean Absolute Error (MAE)
  * Root Mean Squared Error (RMSE)

---

## 📊 Results

* Successfully captured seasonal patterns in passenger data
* Model provides reasonable short-term forecasts
* Demonstrates effectiveness of ARIMA-based forecasting for time series data

---

## 🚀 How to Use

1. Clone the repository:

```bash
git clone https://github.com/AbdenacerKerrouche/Airline_Passengers_Forecasting.git
```

2. Open the project:

* Navigate to the folder
* Open `Passengers_forcating.ipynb` in your browser

---

## 🧰 Requirements

To reproduce this project:

* Python 3.x
* pandas
* numpy
* matplotlib
* statsmodels
* sklearn

---

## 👤 Author

*Kerrouche Abdenacer*

---

## 📄 License

This project is licensed under the MIT License.
