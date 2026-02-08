# 📊 Sales & Demand Forecasting System – Machine Learning Project

## 📝 Project Overview

This project implements a complete **sales and demand forecasting system** using historical business data.  
It combines **Machine Learning** and **Time Series** techniques to generate accurate and business‑friendly forecasts.

Sales forecasting helps organizations:

- Plan inventory efficiently  
- Optimize cash flow  
- Prepare staffing needs  
- Reduce overstock and shortages  

This project was developed as part of **Machine Learning Task 1 – Future Interns (2026).**

---

## 🎯 Objectives

- Forecast future sales using historical data  
- Engineer time‑based features for improved prediction  
- Compare Machine Learning vs Time Series approaches  
- Visualize forecast results  
- Provide actionable business insights  

---

## 🗂️ Project Structure

```text
FUTURE_ML_01/
│
├── data/
│   └── sales_data.csv
│
├── notebook/
│   └── sales_forecasting.ipynb
│
├── README.md
├── .gitignore
└── requirements.txt
```

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit‑learn  
- Statsmodels (ARIMA)  
- Matplotlib  

---

## 📈 Forecasting Models

### 🔹 Machine Learning Model
- Random Forest Regressor  
- Lag features & rolling averages  
- Calendar‑based variables  

### 🔹 Time Series Model
- ARIMA trend forecasting  

---

## 📊 Model Evaluation

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

These metrics quantify forecasting accuracy.

---

## 📉 Visual Results

Forecast visualizations include:

- Historical vs predicted sales  
- 30‑day future forecast  
- Machine Learning vs ARIMA comparison  

Screenshots are included for business clarity.

---

## Business Insights

- Sales show steady long‑term growth  
- Forecasts indicate rising demand  
- Businesses can proactively scale inventory  
- Data‑driven planning reduces operational risks  

---

## How to Run the Project

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Launch Jupyter

```bash
jupyter notebook
```

### 3. Open the notebook

```
notebook/sales_forecasting.ipynb
```

---

## requirements.txt

```text
pandas
numpy
scikit-learn
statsmodels
matplotlib
```

---

## Key Learnings

- Time‑series data preparation  
- Feature engineering for forecasting  
- Regression & ARIMA modeling  
- Forecast evaluation methods  
- Business‑oriented visualizations  

---

## Acknowledgement

This project was developed as part of the  
**Future Interns – Machine Learning Internship Program (2026).**