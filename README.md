# 🛒 Store Item Demand Forecasting

This repository contains my solution to the [Store Item Demand Forecasting Challenge](https://www.kaggle.com/competitions/demand-forecasting) hosted on Kaggle. The goal of this challenge is to accurately predict item-level sales for a retail store chain based on historical sales data.

---

## 📊 Problem Statement

Given daily historical sales data for 50 different items across 10 stores, the objective is to predict the unit sales for each item at each store for the next 3 months. This is a time series forecasting problem with applications in inventory management and supply chain optimization.

---

## 🧠 Approach

The problem was approached using time series modeling and machine learning techniques. Key steps included:

- 📅 **Date feature engineering** (e.g., day, week, month, holiday indicators)
- 🧹 **Data preprocessing** (handling missing values, log transformation)
- 🔍 **Exploratory Data Analysis (EDA)**
- 📈 **Modeling using machine learning algorithms**:
  - XGBoost / LightGBM
  - Prophet / ARIMA (optional exploration)
- 🎯 **Evaluation using RMSE**

---

## 📁 Project Structure


---

## 🔧 Tools & Technologies

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost / LightGBM
- Prophet / ARIMA (optional)
- Kaggle API

---

## 📌 Results

- Baseline RMSE achieved: **[Insert RMSE score]**
- Improved model RMSE: **[Insert updated RMSE]**
- Submission score on Kaggle: **[If available]**

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/AnasGhazi/sales-forecast-ML.git
   cd sales-forecast-ML

