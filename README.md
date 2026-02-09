# Portfolio Time Series Analysis using Python

## 📌 Project Overview

This project focuses on **time series analysis and visualization of a financial portfolio** using Python. It analyzes historical closing prices of selected assets to understand trends, seasonality, and volatility patterns. The notebook applies **seasonal decomposition** and **rolling statistics** to extract meaningful insights from financial time series data.

The analysis is useful for beginners and intermediate learners in **Data Science, Financial Analytics, and Time Series Analysis**.

---

## 📂 Dataset Description

The dataset (`portfolio_data.csv`) contains historical closing prices of multiple assets, including:

* **AMZN** – Amazon
* **DPZ** – Domino's Pizza
* **BTC** – Bitcoin
* **NFLX** – Netflix

Each row represents price values for a specific date.

---

## 🛠️ Technologies & Libraries Used

* **Python**
* **Pandas** – Data loading and manipulation
* **Matplotlib** – Data visualization
* **Statsmodels** – Seasonal decomposition of time series

---

## 📊 Analysis Performed

### 1️⃣ Data Loading & Preprocessing

* Imported financial data using Pandas
* Converted the `Date` column into a datetime format
* Set the date column as the index for time series operations

### 2️⃣ Time Series Visualization

* Plotted closing prices of multiple assets (Amazon, Domino's Pizza, Bitcoin)
* Compared price movements over time

### 3️⃣ Seasonal Decomposition

Applied **multiplicative seasonal decomposition** to identify:

* **Trend** – Long-term movement
* **Seasonality** – Repeating patterns
* **Residuals** – Irregular components

Seasonal decomposition was performed individually for:

* Amazon (AMZN)
* Bitcoin (BTC)
* Netflix (NFLX)

### 4️⃣ Rolling Statistics

* Calculated **30-day rolling mean**
* Calculated **30-day rolling standard deviation**
* Visualized volatility and trend smoothing for Amazon stock

---

## 📈 Key Insights

* Clear trend and seasonal patterns observed in stock prices
* Bitcoin shows higher volatility compared to traditional stocks
* Rolling statistics help identify periods of high and low market volatility

---

## 🚀 How to Run the Project

1. Clone this repository

   ```bash
   git clone <git clone https://github.com/Lucky-sa/TIME-SERIES-ANALYSIS.git>
   ```
2. Install required libraries

   ```bash
   pip install pandas matplotlib statsmodels
   ```
3. Open the notebook

   ```bash
   jupyter notebook MYPROJECT.ipynb
   ```
4. Ensure `portfolio_data.csv` is present in the working directory

---

## 🎯 Future Improvements

* Add forecasting models (ARIMA / SARIMA / LSTM)
* Perform correlation analysis between assets
* Include more financial indicators
* Build an interactive dashboard

---

## 👤 Author

**Sai**
Aspiring Data Scientist | Machine Learning Enthusiast
