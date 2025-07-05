# 🛫 Air Passengers Time Series Forecasting

This project focuses on forecasting the number of international **air passengers** over time using classical time series models such as **ARIMA** and **SARIMA**. The dataset exhibits clear trends and seasonality, making it ideal for exploring and comparing forecasting techniques.

---

## 📁 Repository Contents

```
📦 stock_market_analysis/
├── 2timeseriesanalysis.ipynb        # Jupyter notebook with all analysis
├── AirPassengers.csv                # Dataset with monthly airline passenger numbers
└── README.md                        # Project overview
```

---

## 📌 Project Objectives

* Explore and visualize the air passenger dataset
* Test for stationarity and apply necessary transformations
* Fit ARIMA and SARIMA models
* Forecast future passenger traffic
* Evaluate model performance using statistical metrics

---

## 📊 Dataset Description

* **Features**:

  * `Month`: Time (monthly from 1949 to 1960)
  * `#Passengers`: Number of air passengers

This dataset is a classic benchmark for seasonal time series forecasting.

---

## 🧠 Models Used

* **ARIMA** – Captures trend and autoregressive components
* **SARIMA** – Extends ARIMA to model seasonality

### 📈 Evaluation Metrics

* **MAE** – Mean Absolute Error
* **RMSE** – Root Mean Squared Error
* **R² Score** – Coefficient of Determination


## ▶️ How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/mphfernando/airpassenger_analysis.git
   cd airpassenger_analysis
   ```

2. **Install Requirements**

   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
   ```

3. **Open Jupyter Notebook**

   ```bash
   jupyter notebook 2timeseriesanalysis.ipynb
   ```

---

## 📚 Tools & Libraries

* Python
* pandas, numpy
* matplotlib, seaborn
* statsmodels
* scikit-learn

---
