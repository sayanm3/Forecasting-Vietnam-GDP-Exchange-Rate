# Forecasting Projects

This repository contains two forecasting projects: **GDP Forecasting Using ETS Model** and **Vietnam Exchange Rate Forecast Using ARIMA**. Both projects leverage data from the World Bank and utilize different tools and methodologies to analyze and predict future trends.

---

## 1. Vietnam GDP Forecasting Using ETS Model

### 📖 Introduction
This project focuses on forecasting GDP using the Exponential Smoothing (ETS) model. The objective is to analyze historical GDP data and predict future values, providing insights for economic planning and decision-making.

### 📊 Data Source
- The dataset was sourced from the **World Bank Open Data** portal.

### 🎯 Objective
To forecast GDP trends by analyzing historical data, enabling better resource allocation and investment decisions.

### 🛠️ Tools and Techniques
- **Tools:** Microsoft Excel
- **Techniques:** 
  - Exponential Smoothing (ETS)
  - Trend Analysis
  - Error metrics (MAPE)

### 📐 Methodology
1. **Data Collection and Preprocessing:**
   - Extracted GDP data from the World Bank and cleaned it in **Microsoft Excel**.
2. **Exploratory Data Analysis (EDA):**
   - Performed descriptive statistics and visualized GDP trends.
3. **ETS Modeling:**
   - Applied the Exponential Smoothing (ETS) model to capture trends and seasonality.
4. **Validation:**
   - Evaluated model performance using **Mean Absolute Percentage Error (MAPE)**.

### ✅ Conclusion
The ETS model effectively forecasted GDP trends, providing reliable insights for economic growth prediction. The findings assist in policymaking, business strategy, and investment planning. While the model assumes historical trends will persist, it offers a robust framework for macroeconomic forecasting.

---

## 2. Vietnam Exchange Rate Forecast Using ARIMA

### 📖 Introduction
This project predicts the exchange rate of the Vietnamese Dong (VND) against the US Dollar (USD) using the ARIMA model. The analysis offers valuable insights for financial decision-making and risk management.

### 📊 Data Source
- The dataset, covering 1986 to 2022, was sourced from the **World Bank Open Data** portal.

### 🎯 Objective
To forecast USD/VND exchange rates using historical data, providing actionable insights for financial institutions, traders, and policymakers.

### 🛠️ Tools and Libraries
- **Tools:** Python (Jupyter Notebook)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, pmdarima

### 📐 Methodology
1. **Data Collection and Preprocessing:**
   - Imported and cleaned the data in **Python**.
2. **Exploratory Data Analysis (EDA):**
   - Visualized historical trends using **Matplotlib**.
   - Conducted stationarity testing with the **Augmented Dickey-Fuller (ADF)** test.
3. **Model Selection and Fitting:**
   - Identified the optimal ARIMA configuration using **pmdarima's auto_arima**.
   - Fitted an **ARIMA(1,1,0)** model to the training data.
4. **Validation and Forecasting:**
   - Split data into training and testing sets.
   - Predicted future values and validated accuracy using **Root Mean Squared Error (RMSE)**.

### ✅ Conclusion
The ARIMA model provided accurate forecasts for the USD/VND exchange rate, capturing historical trends effectively. These insights can guide currency risk management, financial planning, and policy development. Future enhancements could incorporate external factors like inflation or trade balance to improve prediction accuracy.
