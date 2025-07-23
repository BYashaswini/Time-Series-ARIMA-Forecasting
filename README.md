# 📈 Energy Demand Forecasting using ARIMA

This project performs time series analysis and forecasting of **energy load and solar power generation** in Italy for 2016, using the **ARIMA model**. It includes data preprocessing, stationarity checks, ARIMA modeling, and visual forecasting.

---

## 🧠 Objectives
- Analyze historical energy demand and solar generation.
- Apply ARIMA-based time series modeling for accurate forecasting.
- Visualize actual vs. predicted values for performance evaluation.

---

## 📁 Dataset
- Source CSV: [TimeSeries_TotalSolarGen_and_Load_IT_2016.csv](https://data.open-power-system-data.org/time_series/2020-10-06/time_series_60min_singleindex.csv)
- Filtered for:
  - Italy (`IT_load_new`, `IT_solar_generation`)
  - Year: 2016

---

## ⚙️ Methods Used
- Time series preprocessing (datetime conversion, resampling)
- ADF Test for stationarity
- Differencing and transformation for trend removal
- ACF and PACF analysis to determine ARIMA (p, d, q)
- Model fitting with `statsmodels`
- Forecasting and residual error analysis

---

## 📊 Key Visualizations
- Load and solar generation over time
- Differenced series
- ACF and PACF plots
- Forecast vs. actual plots

---

## 📦 Libraries Used
- `pandas`, `numpy`, `matplotlib`, `statsmodels`
- `seaborn` (for advanced plots)

---

## 🚀 How to Run
1. Clone this repo  
2. Open the notebook in Jupyter or [Google Colab](https://colab.research.google.com/)  
3. Download and place the dataset in the same directory  
4. Run each cell in order

---

## 📌 Future Work
- Compare with SARIMA or Facebook Prophet
- Add external regressors (e.g., temperature) with ARIMAX
- Deploy using Streamlit for interactive forecasting
