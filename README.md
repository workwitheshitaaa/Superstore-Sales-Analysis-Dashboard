# Superstore Sales Analysis & Power BI Dashboard

This project analyzes the Superstore dataset using **Python** and **Power BI** to uncover sales trends, customer behavior, and product-level insights.  
It includes:

- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Random Forest model for sales prediction  
- A fully interactive Power BI dashboard  
- Business KPIs and insights  

---

## 🔧 Tools & Technologies

- **Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)**
- **Power BI (DAX Measures, KPIs, interactive visuals)**
- **Jupyter/Google Colab**

---

## 1. Data Cleaning Steps

- Handled missing values  
- Converted date columns  
- Removed outliers using IQR  
- Added new columns:
  - `Profit Margin`
  - `Year`, `Month`, `Day` (for time-based visuals)

---

## 2. Exploratory Data Analysis

Key analysis includes:

- Month-wise sales trend  
- Category-wise sales & profit insights  
- State and region performance  
- Sales vs Profit scatter plot  
- Correlation heatmap  

Visualizations created using **matplotlib + seaborn**.

---

## 3. Machine Learning (Random Forest)

Built a **RandomForestRegressor** to predict **Sales** using:

- Quantity  
- Discount  
- Profit  
- Category & Sub-category (label encoded)

Outputs:

- Feature importance  
- Predicted vs actual plot  
- Model accuracy metrics (RMSE, R²)

---

## 4. Power BI Dashboard

Dashboard includes:

### Visuals
- Sales by Category  
- Month-wise Sales Trend  
- State-wise Sales Map  
- Profit vs Sales Scatter Plot  
- Top Products by Sales  
- Loss / Return analysis  

### KPI Cards
- Total Sales  
- Total Profit  
- Average Profit Margin  
- Highest Selling Category  
- Year-over-Year Growth  

DAX measures used:
- Total Sales  
- Total Profit  
- Profit Margin %  
- YoY Sales Growth  
- Product Rank  

---

## Insights

- Technology segment generates the highest revenue.  
- Furniture has high sales but low profit margin.  
- East and West regions dominate overall sales.  
- Discounts significantly reduce profit in several categories.  
