# ⛽ Fuel Price Insights: Analysing Historical Trends and Predicting Future Price Movements

📊 A time series forecasting project using ARIMA and SARIMA models to analyze and predict weekly fuel prices in Italy, with an interactive dashboard built using Streamlit.

---

## 🚀 Deployment Details

- **Web App:** [https://fuel-price-insights.streamlit.app/](https://fuel-price-insights.streamlit.app/)

---

## 📌 Project Overview

### 🎯 Purpose

This project aims to:

- Forecast future fuel prices using ARIMA and SARIMA models.
- Decompose fuel price time series into trend, seasonality, and residuals.
- Identify volatility and change points in historical prices.
- Provide interactive visualizations and insights via a Streamlit dashboard.

---

### 🛠 How the Project is Built

#### 🐍 Python Libraries
- **pandas** – Data manipulation and preprocessing
- **numpy** – Numerical operations
- **matplotlib & seaborn** – Data visualization
- **statsmodels** – Time series decomposition and modeling
- **scikit-learn** – Data scaling (MinMaxScaler)

#### 🎛 Streamlit Features
- Interactive dropdowns, sliders, buttons
- Real-time updates
- Easy web deployment

The app structure separates data loading, modeling, and visualization into modular scripts for maintainability.

---

### 📂 Dataset

- **Source:** Ministry of Environment and Energy Security, Italy
- **Coverage:** March 2005 to November 2022 (Weekly Data)
- **Access:** [Weekly Fuel Prices in Italy](https://data.world)
- **License:** IODL 2.0

---

## 🔍 Model Functionalities

### 🧹 Data Preprocessing
- Averaging duplicate weekly prices
- Linear interpolation for missing weeks

### 📉 Time Series Decomposition
- Trend, seasonality, residual breakdown using additive decomposition

### 📈 Time Series Visualization
- Box plots, autocorrelation, and trend analysis

### 🧪 Stationarity Checks
- Augmented Dickey-Fuller test
- Differencing applied where needed

### 🧠 Forecasting Models
- ACF & PACF analysis for model selection
- Comparison via AIC/BIC
- Residual diagnostics and Q-Q plots
- SARIMA preferred for seasonal accuracy

### 🔮 Predictions
- Short- and long-term forecasting
- Confidence intervals included

---

## 💻 Web App Functionalities

### Dashboard Features
- 🔘 Fuel product selector
- 📋 Dataset snapshot
- 📊 Interactive trend plots
- 📆 Forecasting with user-defined horizons
- ⚙️ Model selection (ARIMA or SARIMA)

Despite complex statistical modeling, the dashboard maintains ease of use and accessibility for non-technical users.

---

## 🧩 Issues and Contributions

### ❗ Initial Challenges

#### With Dash:
- Inefficient callbacks
- Hosting/deployment issues

#### With Streamlit:
- ML model serialization issues
- Environment dependency management
- Code organization for maintainability

### ✅ Solutions Implemented
- Used `pickle`/`joblib` for model serialization
- Modularized code into reusable scripts
- Streamlined deployment with environment handling

---

## 🏁 Conclusion

Fuel Price Insights bridges advanced statistical modeling and interactive design:

- SARIMA models provided robust seasonal forecasts
- Interactive Streamlit dashboard enabled intuitive user experience
- Forecasts offer valuable insights for economic planning and energy market analysis

### 📌 Future Work
- Experiment with other time series models (e.g., Prophet, LSTM)
- Integrate macroeconomic indicators
- Extend dataset with more fuel types or other countries

---
