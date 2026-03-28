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
<img width="1421" height="797" alt="image" src="https://github.com/user-attachments/assets/d549d62d-5e59-4c3e-8bbc-bc61bb4ee8cf" />
<img width="1419" height="806" alt="image" src="https://github.com/user-attachments/assets/36eac05a-6668-4527-b47d-fbfcc7051e27" />
<img width="1414" height="796" alt="image" src="https://github.com/user-attachments/assets/6b63cc3a-6625-4c6f-b711-69e9234080be" />
<img width="1419" height="795" alt="image" src="https://github.com/user-attachments/assets/a34bf5ac-0264-4a33-8af0-a5d0d40a1626" />

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


