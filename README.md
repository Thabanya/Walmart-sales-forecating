# Walmart-sales-forecating
End-to-end data analysis and machine learning project predicting retail weekly sales using Linear Regression, Random Forest, and XGBoost.
# 🛒 Walmart Sales Forecasting

## 📌 Project Overview
This project focuses on predicting **weekly sales for Walmart stores** using machine learning techniques. The goal is to understand sales patterns and build a model that can accurately forecast future sales.

---

## 📂 Dataset
The dataset contains:
- **Train Data** – Historical weekly sales
- **Test Data** – Unseen data for prediction
- **Store Data** – Store type and size information

### Key Features:
- Store
- Department
- Weekly_Sales (Target)
- Holiday_Flag
---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed analysis to understand the data:

- ✅ Checked missing values
- ✅ Analyzed **negative sales (returns/refunds)**
- ✅ Compared **store types (A, B, C)**
- ✅ Studied **holiday vs non-holiday sales**
- ✅ Identified **monthly & weekly seasonality**
- ✅ Correlation heatmap analysis
- ✅ Department-level performance analysis

---

## ⚙️ Feature Engineering

- Extracted:
  - Year
  - Month
  - Week
- Encoded categorical features (Store Type)
- Prepared data for machine learning models

---

## 🤖 Models Used

| Model | Description |
|------|------|
| Linear Regression | Baseline model |
| Random Forest | Handles non-linearity |
| XGBoost | Boosting-based model |

---

## 📊 Model Performance

| Model | R² Score |
|------|------|
| Linear Regression | 0.08 |
| Random Forest | 0.97 ✅ |
| XGBoost | 0.85 |

👉 **Random Forest performed best**, capturing complex patterns in sales data.

---

## 📈 Key Insights

- 🏪 **Store Type A** performs best overall
- 📅 **Holiday weeks increase sales significantly**
- 📊 Certain **departments contribute more revenue**
- 🔄 Strong **seasonal trends** in weekly sales
- ❌ Negative sales occur due to returns/refunds but have low impact

---

## 📉 Visualizations

- Monthly Sales Trend
- Weekly Seasonality Pattern
- Holiday vs Non-Holiday Sales
- Sales by Store Type
- Actual vs Predicted Sales

---

## 🧠 Conclusion

Machine learning models, especially **Random Forest**, are effective for sales forecasting when multiple features are involved.  
The model can help businesses:

- Improve inventory planning
- Optimize staffing
- Make better business decisions

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Try time-series models (ARIMA, SARIMA)
- Deploy model using Streamlit
- Real-time prediction system

---

## 👤 Author

**Thabanya**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
