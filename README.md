# E-Commerce-Sales-Analytics-PowerBI
Power BI dashboard analyzing e-commerce sales, product performance, and customer behavior using DAX and star schema modeling.

# 📊 E-Commerce Sales Analytics Dashboard (Power BI)
This project presents an end-to-end business intelligence solution using Power BI to analyze e-commerce sales performance, customer behavior, and product profitability.

The dashboard enables stakeholders to track KPIs, identify trends, and make data-driven decisions.

## 🌐 Live Dashboard

[View Dashboard](https://app.powerbi.com/links/g000hH5IaL?ctid=68925209-7378-4959-87b9-88ea918ae4e0&pbi_source=linkShare&bookmarkGuid=fea7b252-4e34-4bde-a604-0b52ac5efc2f)

## 🚀 Key Features

- Executive KPI Overview (Sales, Profit, Orders, Margin)
- Product Performance Analysis (Top products, profitability)
- Customer Segmentation Insights
- Customer Retention & Repeat Purchase Analysis
- Regional Sales Distribution
- Interactive filters (Year, Region, Category, Segment)

## 📸 Dashboard Preview
<img width="1325" height="744" alt="image" src="https://github.com/user-attachments/assets/40d78633-48c8-4497-90fd-202be94884b7" />
<img width="1323" height="748" alt="image" src="https://github.com/user-attachments/assets/e3a8bea4-3a1a-4476-8dc1-e312d1fffa46" />
<img width="1322" height="747" alt="image" src="https://github.com/user-attachments/assets/eb0ebbbd-3902-4807-8f96-df97d36f7dc4" />

## 🧩 Data Model

- Fact Table: Sales Transactions
- Dimension Tables:
  - Customer
  - Product
  - Date
  - Region

Star schema implemented for optimized performance.

## 📐 Key DAX Measures

Total Sales = SUM(Fact_Sales[Sales])

Total Profit = SUM(Fact_Sales[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

Avg Revenue per Customer = 
DIVIDE([Total Sales], DISTINCTCOUNT(Dim_Customer[Customer ID]))

Retention Rate =
DIVIDE([Returning Customers], [Total Customers])

## 📊 Business Insights

- Technology category generates the highest revenue
- Consumer segment contributes majority of sales
- Discounts negatively impact profitability in certain categories
- Repeat customers contribute significantly to revenue

## 🛠 Tools & Technologies

- Power BI
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)
- Excel / CSV dataset

## ▶️ How to Use

1. Download the .pbix file
2. Open in Power BI Desktop
3. Interact with filters and visuals

## 👤 Author

Arghyajyoti Samui  
Data Analyst | Power BI | SQL | Python  


