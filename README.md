# Dashboard-Assignment
📊 Power BI Sales Dashboard analyzing Total Sales, Profit, Profit Margin, Region Performance, Top Products &amp; Month-wise Trends using DAX.


📊 Power BI Sales Analysis Dashboard

🚀 Project Overview

This project is a Power BI Final Assignment Dashboard created to analyze sales performance using interactive visualizations and DAX measures.

The dashboard provides insights into Total Sales, Total Profit, Profit Margin, Region-wise performance, State-wise profit, Product performance, and Month-wise sales trends.

📌 Objectives

- Analyze total sales and profit
- Identify highest performing region
- Find most profitable product category
- Determine best-performing salesperson
- Track month-wise sales trends
- Analyze state-wise and region-wise profit contribution

📊 Dashboard KPIs

- 💰 Total Sales: 4M+
- 📈 Total Profit: 549K+
- 📊 Profit Margin: Calculated using DAX
- 🌍 Region-wise Sales Analysis
- 🏆 Top 5 Products by Sales
- 👨‍💼 Salesperson Performance
- 📅 Month-wise Sales Trend
- 🗺 City & State Profit Distribution

🛠 Tools & Technologies Used

- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Data Cleaning in Power Query
- Excel Dataset

📐 Key DAX Measures Used

```DAX
Total Sales = SUM(Sales[SalesAmount])
Total Profit = SUM(Sales[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
