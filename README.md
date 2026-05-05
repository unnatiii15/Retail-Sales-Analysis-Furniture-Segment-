# 📊 Sales Analytics & Dashboard Project

## 🚀 Overview

This project is an end-to-end data analytics workflow combining **data cleaning, exploratory analysis, feature engineering, and visualization** to uncover actionable business insights from retail sales data.

The project also includes a **Power BI dashboard** to present insights in a clear, decision-oriented format.

---

## 📂 Dataset

* **Records:** 2,121 transactions
* **Features:** 27
* Includes: Sales, Profit, Discount, Subcategory, Region, Order Date, Delivery metrics

---

## 🧠 Project Workflow

### 🔹 1. Data Cleaning & Preparation

* Removed duplicates and handled missing values
* Converted date columns and created time-based features (month, day, etc.)
* Engineered new features such as delivery time

---

### 🔹 2. Exploratory Data Analysis (EDA)

* Identified seasonal sales trends
* Analyzed relationships between discount and profit
* Evaluated product category and regional performance

---

### 🔹 3. Modeling & Evaluation

* Built predictive models using:

  * Linear Regression
  * Random Forest Regressor

* Compared performance using:

  * R² Score
  * Mean Absolute Error (MAE)

* Observed that:

  * Linear Regression performed better on this dataset
  * Random Forest showed poor generalization (negative R²), indicating overfitting

---

### 🔹 4. Visualization (Power BI Dashboard)

![Dashboard](images/r_dashboard.png)

---

## 🔍 Key Insights

* 📈 **Sales Trend:**
  Sales peak in November–December → strong seasonal demand

* 🪑 **Product Performance:**
  Chairs drive highest revenue and profit → core category

* 💸 **Profitability:**
  Tables show negative profit → pricing or cost inefficiency

* 🌍 **Regional Analysis:**
  West region leads in sales, South underperforms

* 🎯 **Discount Impact:**
  Higher discounts reduce profitability → margin trade-off

---

## 📊 Key Metrics

* **Total Sales:** ₹742K
* **Total Profit:** ₹18.5K
* **Average Discount:** 17%

---

## 🛠️ Tech Stack

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Visualization:** Power BI
* **Environment:** Jupyter Notebook

---

## 💡 Business Value

This project demonstrates how data can be used to:

* Identify high-performing and loss-making products
* Understand seasonal demand patterns
* Support pricing and discount decisions
* Improve strategic planning

---

## 📌 Future Improvements

* Hyperparameter tuning for improved model performance
* Customer segmentation analysis
* Deployment of dashboard with real-time data

---

## 🔗 Author

**Unnati Bhanushali**
GitHub: https://github.com/unnatiii15

---

### 💸 Discount vs Profit

* Moderate negative correlation (**-0.48**) between discount and profit
* Higher discounts reduce overall profitability

---

### 🪑 Subcategory Analysis

* Furnishings (~45%) and Chairs (~29%) dominate transaction volume
* Key drivers of product demand

---

### 📊 Sales Behavior

* Sales distribution shows variability across months and product types
* Useful for demand forecasting and stock planning

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Jupyter Notebook

---

## 📊 Visualizations

*(Add plots here later)*

---

## 📈 Future Improvements

* Add Power BI dashboard
* Expand dataset beyond furniture category
* Perform deeper profitability analysis

---

## 💡 Key Learning

* Understanding seasonal demand patterns
* Evaluating pricing impact on profit
* Translating data into business insights

---

## 🔗 Author

**Unnati Bhanushali**
GitHub: https://github.com/unnatiii15
