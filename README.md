# 🛍️ End-to-End Retail Sales Analysis & Sales Prediction

## 📌 Project Overview
This project focuses on analyzing retail sales data to uncover valuable business insights and build a Machine Learning model for sales prediction. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, visualization, model building, and dashboard creation using Power BI.

---

## 🎯 Objectives
- Analyze retail sales performance.
- Identify sales trends and customer purchasing patterns.
- Discover top-performing products, categories, and regions.
- Predict future sales using Machine Learning.
- Build an interactive dashboard for business decision-making.

---

## 📂 Dataset Information

**Dataset:** Retail Sales Dataset

### Features
| Column | Description |
|---------|-------------|
| Order ID | Unique order identifier |
| Order Date | Date of purchase |
| Ship Date | Shipping date |
| Ship Mode | Shipping method |
| Customer ID | Customer identifier |
| Customer Name | Customer name |
| Segment | Customer segment |
| Country | Country |
| City | Customer city |
| State | Customer state |
| Region | Sales region |
| Product ID | Product identifier |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Product name |
| Sales | Sales amount |
| Quantity | Quantity sold |
| Discount | Discount offered |
| Profit | Profit earned |

---

# 🛠️ Tools & Technologies Used

### Programming
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

### Machine Learning
- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor
- XGBoost (if used)
- Model Evaluation Metrics (R², MAE, RMSE)

### Data Visualization
- Matplotlib
- Seaborn
- Power BI

### Development Environment
- Jupyter Notebook
- Git & GitHub

---

# 📊 Exploratory Data Analysis (EDA)

The dataset was explored using various visualization techniques to understand customer behavior and business performance.

### Visualizations Included

- Sales by Category
- Sales by Sub-Category
- Monthly Sales Trend
- Regional Sales Distribution
- Profit by Region
- Top Selling Products
- Sales vs Profit
- Correlation Heatmap
- Discount Impact on Profit
- Customer Segment Analysis

---

# 📈 Key Business Insights

### 📌 Sales Performance
- Technology category generated the highest sales.
- Office Supplies had the highest number of orders.
- Furniture showed comparatively lower profit margins.

### 📌 Regional Insights
- West Region generated the highest revenue.
- Central Region experienced lower profitability.

### 📌 Customer Analysis
- Consumer Segment contributed the largest share of sales.
- Corporate customers generated higher average order values.

### 📌 Product Analysis
- A few products contributed significantly to total sales.
- Certain sub-categories generated high sales but low profits.

### 📌 Discount Analysis
- Higher discounts often resulted in lower profits.
- Moderate discounts improved customer purchases without heavily affecting profit.

### 📌 Time Series Analysis
- Sales showed seasonal trends.
- Peak sales occurred during festive/end-of-year periods.

### 📌 Correlation Analysis
- Sales and Profit showed a positive correlation.
- Discount negatively affected Profit.
- Quantity had a moderate relationship with Sales.

---

# 🤖 Machine Learning Model

## Problem Statement
Predict future retail sales using historical transaction data.

### Workflow
- Data Cleaning
- Feature Engineering
- Train-Test Split
- Model Training
- Model Evaluation
- Sales Prediction

### Models Evaluated
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

# 📊 Power BI Dashboard

The dashboard provides interactive visualizations including:

- Total Sales
- Total Profit
- Total Orders
- Monthly Sales Trend
- Regional Performance
- Category-wise Sales
- Segment Analysis
- Top Products
- Filters for Region, Category, and Year

---

# 📁 Project Structure

```
Retail-Sales-Analysis/
│
├── data/
│   └── Retail_sales.csv
│
├── notebooks/
│   └── Retail_Sales_Analysis.ipynb
│
├── dashboard/
│   └── Retail_Sales_Dashboard.pbix
│
├── models/
│   └── sales_prediction_model.pkl
│
├── images/
│   └── dashboard.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 🚀 Future Improvements

- Deploy the ML model using Streamlit or Flask.
- Build a real-time sales forecasting application.
- Automate dashboard updates.
- Integrate cloud database support.
- Experiment with advanced forecasting models like XGBoost and LSTM.

---

# 📌 Results

✔ Cleaned and analyzed retail sales data.

✔ Generated actionable business insights.

✔ Built predictive machine learning models.

✔ Created an interactive Power BI dashboard.

✔ Demonstrated an end-to-end Data Analytics & Data Science workflow.

---

# 📷 Dashboard Preview

> Add screenshots of your Power BI dashboard and important visualizations here.

Example:

```
images/dashboard.png
images/correlation_heatmap.png
images/monthly_sales.png
```

---

# ⭐ Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Business Intelligence
- Machine Learning
- Sales Forecasting
- Power BI Dashboarding
- Python Programming
- Git & GitHub

---
# 📌 Conclusion

This project successfully demonstrates an end-to-end retail sales analytics and sales prediction workflow by combining data analysis, business intelligence, and machine learning techniques. Through comprehensive data cleaning, exploratory data analysis (EDA), and visualization, valuable insights into customer behavior, product performance, regional sales, and profitability were identified.

The analysis revealed that factors such as product category, customer segment, region, and discount strategy significantly influence sales and profit. The interactive Power BI dashboard enables stakeholders to monitor key performance indicators (KPIs) and make informed business decisions with ease.

Additionally, a machine learning model was developed to forecast future sales based on historical data. The model provides reliable predictions that can support inventory planning, demand forecasting, and strategic business decisions.

Overall, this project showcases practical skills in **Python, Data Analysis, Data Visualization, Machine Learning, and Power BI**, demonstrating how raw retail data can be transformed into actionable business insights and predictive solutions for data-driven decision-making.
