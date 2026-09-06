# Superstore Sales Analytics & Forecasting

## 📊 Project Overview

This project focuses on analyzing Superstore sales data and forecasting future sales using Python, Prophet, and Tableau.

The project covers the complete data analytics workflow, including data cleaning, exploratory data analysis, time-series forecasting, model evaluation, and dashboard development.

---

## 🎯 Objectives

- Analyze historical sales and profit performance
- Identify sales trends and patterns
- Understand sales performance across regions and sub-categories
- Forecast future sales using time-series forecasting
- Evaluate the forecasting model
- Build an interactive Tableau dashboard for business insights

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Prophet
- Google Colab / Jupyter Notebook
- Tableau

---

## 🔄 Project Workflow

```text
Superstore Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis (EDA)
        ↓
Sales Aggregation
        ↓
Prophet Time-Series Forecasting
        ↓
Model Evaluation
        ↓
Tableau Dashboard
````

---

## 📈 Key Results

| Metric            |         Value |
| ----------------- | ------------: |
| Total Sales       | ₹2,297,200.86 |
| Total Profit      |   ₹286,397.02 |
| Total Orders      |         5,009 |
| Forecast Accuracy |        81.93% |
| MAPE              |        18.07% |
| MAE               |    ₹15,164.52 |
| RMSE              |    ₹18,853.47 |

---

## 🔮 Sales Forecasting

Prophet was used to forecast future sales based on historical sales patterns.

The forecasting model was trained using historical sales data and used to predict sales for the first six months of 2018.

### Forecast Period

**January 2018 – June 2018**

The forecast dataset contains:

* Forecast Sales
* Lower Forecast Bound
* Upper Forecast Bound
* Actual Sales
* Data Type
* Year
* Month
* Quarter

---

## 📊 Tableau Dashboard

The Tableau dashboard provides an overview of:

* Total Sales
* Total Profit
* Total Orders
* Sales Trend
* Sales by Sub-Category
* Sales by Region
* Actual vs Forecast Sales

### Dashboard Preview

![Superstore Sales Dashboard](screenshots/dashboard.png)

---

## 📁 Project Structure

```text
superstore-sales-analytics/
│
├── data/
│   └── cleaned_superstore.csv
│
├── notebooks/
│   └── sales_forecasting.ipynb
│
├── tableau/
│   └── Superstore_Sales_Analytics_Prophet.twbx
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

---

## 💡 Key Insights

The analysis provides insights into:

* Overall sales and profit performance
* Monthly sales trends
* Regional sales performance
* Sub-category sales performance
* Future sales expectations based on historical patterns

---

## 🚀 How to Use

### Python Notebook

The complete data analysis and forecasting workflow is available in the `notebooks` folder.

### Tableau Dashboard

The Tableau workbook is available in the `tableau` folder.

The `.twbx` file contains the Tableau dashboard and packaged data sources.

---


