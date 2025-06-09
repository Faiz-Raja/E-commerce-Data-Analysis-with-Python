# E-commerce-Data-Analysis-and-Insights-with-Python
This project analyzes retail sales data from a sample superstore to uncover business insights using Python-based visualization and data processing. The notebook focuses on identifying key trends in sales and profit performance across various dimensions such as time, category, and customer segment.

## Overview:

This project applies descriptive analytics techniques to explore retail transactions and visualize performance metrics across time and product categories. It leverages Python’s powerful data analysis and visualization libraries to transform raw sales data into meaningful dashboards and insights.

**The project includes:**

• Data loading and preprocessing

• Time-based trend analysis (monthly/yearly)

• Sales and profit analysis by product category and sub-category.

• Customer segmentation analysis

• Interactive visualizations using Plotly Express

---
## Objective

• Understand sales and profit distribution across categories and time periods

• Analyze customer behavior across segments

• Identify underperforming or high-performing product groups

• Present findings using professional, interactive plots

---
## Tools and Techniques

• **Python:** pandas, plotly, datetime

• **Plotly Express:** for interactive charts and dashboards

• **Jupyter Notebook:** primary development environment

• **Dataset:** Superstore.csv (CSV format)

---
## Project Structure

```
├── e commerce project1.ipynb     # Main notebook
├── Superstore.csv                # Dataset used
├── README.md                     # Project documentation (this file)
```

---
## 🔍 Methodology

**🧹 Data Preparation**

• Loaded and inspected dataset using pandas

• Converted Order Date and Ship Date columns to datetime format

• Created new time features: Order Month, Order Year, and Day of Week

---

## **📊 Exploratory Data Analysis (EDA)**

**📈 Monthly Sales Trend**

• Line plot showing total sales per month

• Identified seasonal trends in customer purchasing behavior

**🧴 Sales by Category & Sub-Category**

• Pie charts and bar charts used to visualize which categories and sub-categories contribute most to total sales

**💰 Profit Analysis**

• Compared profitability across months, categories, and sub-categories

• Highlighted areas with high sales but low or negative profit (e.g., discounts, high cost of goods)

**👥 Customer Segment Analysis**

• Aggregated sales and profit data by customer segments (e.g., Consumer, Corporate, Home Office)

• Identified the most profitable customer segments

---

## 📈 Results

**Key Insights:**

• **Technology** and **Office Supplies** consistently outperform in both sales and profits

• **Furniture** shows moderate sales but lower profitability in many sub-categories

• Certain months (e.g., November, December) show sales spikes—likely due to seasonal shopping events

• Consumer segment contributes the highest to total sales, but Corporate segment yields better profit margins

---
## **📊 Visual Dashboard Components**

• **Line Plots:** Monthly trends in sales and profit

• **Pie Charts:** Category-wise breakdowns

• **Bar Charts:** Sub-category level performance

• **All visuals are interactive and built using plotly.express**

---

## **📚 Appendix**

**Dataset Columns:**

Order Date, Ship Date, Category, Sub-Category, Sales, Profit, Quantity, Region, Segment

**Python Libraries Used:**

pandas, plotly, datetime

---
