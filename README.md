# E-Commerce-Sales-Analytics-PowerBI
Power BI dashboard analyzing e-commerce sales, product performance, and customer behavior using DAX and star schema modeling.

# 📊 E-Commerce Sales Analytics Dashboard (Power BI)
This project presents an end-to-end business intelligence solution using Power BI to analyze e-commerce sales performance, customer behavior, and product profitability.

The dashboard enables stakeholders to track KPIs, identify trends, and make data-driven decisions.

## 🌐 Live Dashboard 

[View Dashboard](https://app.powerbi.com/links/g000hH5IaL?ctid=68925209-7378-4959-87b9-88ea918ae4e0&pbi_source=linkShare&bookmarkGuid=fea7b252-4e34-4bde-a604-0b52ac5efc2f)

## 📂 Dashboard Architecture

The report is structured into four specialized analytical layers to drive data-driven decisions.

### 1. Executive Performance Overview
Focuses on high-level KPIs and regional health to provide stakeholders with immediate business status.
* **Core Metrics**: Tracks **$2.54M Total Sales** with a robust **36.63% YoY Growth**.
* **Regional Contribution**: Identifies the **South region** as the top performer ($669K), followed closely by Central ($661K).
* **Revenue vs. Profit**: Highlights **Technology** as the primary revenue and profit driver ($857K Sales / $103K Profit).

### 2. Product & Pricing Intelligence
Delivers deep-dives into inventory performance and the impact of pricing strategies.
* **Product Quadrant Analysis**: Uses scatter plots to visualize the correlation between **Weighted Discounts** and **Profit Margins** across sub-categories.
* **Top Performers**: Highlights **Storage Model 567** as the highest sales generator ($3,140) and **Paper Model 399** as a high-profit unit.
* **Category Insights**: Breaks down monthly sales volume by category, including Office Supplies, Technology, and Furniture.

### 3. Customer Segmentation & Geography
Analyzes the "who" and "where" of the business to refine marketing and logistics.
* **Segment Dynamics**: Reveals that the **Consumer segment** contributes the vast majority of revenue ($2.5M) compared to Corporate ($40K).
* **Customer KPIs**: Tracks **Average Order Value ($508)** and **Revenue Per Customer ($5K)**.
* **Geographic Mapping**: Visualizes sales distribution across the United States to identify high-density market zones.

### 4. Time Intelligence & Retention
Utilizes advanced logic to analyze growth momentum and seasonal trends.
* **MoM Growth Tracking**: Analyzes monthly fluctuations, identifying a peak growth of **36.8% in January**.
* **Seasonality Analysis**: Tracks average sales trends to pinpoint high-performance months (July peak at $236K) vs. year-end dips.
* **Retention Metrics**: Monitors customer loyalty with a **1.00 Retention Rate** metric.

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


