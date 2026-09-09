# 📊 E-Commerce Sales & Performance Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black )
![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-blue )
![Power Query](https://img.shields.io/badge/Power_Query-ETL-green )

An interactive, end-to-end Business Intelligence dashboard built in **Power BI** to track Key Performance Indicators (KPIs), analyze trends, and empower data-driven decision-making. This project demonstrates the complete data analysis lifecycle: from raw data extraction and ETL (Power Query), to relational data modeling (Star Schema), and advanced calculations (DAX).

## 💡 Key Business Insights Generated
* **Revenue Trends:** Identified a **24% increase** in Q3 revenue, primarily driven by high-margin conversions in the Electronics category across the West Region.
* **Performance Bottlenecks:** Highlighted a **12% drop** in recurring sales within the Home Appliances segment, providing stakeholders with the data needed to pivot Q4 marketing strategies.
* **Operational Efficiency:** Visualized peak order times (6 PM - 9 PM) and mapped customer demographics, enabling better supply chain and customer support resource allocation.

## 🛠️ Technical Pipeline & ETL Process

### 1. Data Extraction & Cleaning (Power Query)
* Imported raw datasets containing over **50,000+ rows** of transactional and customer data.
* Handled missing values, removed duplicates, and standardized data types across multiple regional files.
* Created conditional columns and merged queries to enrich the dataset for deeper geographic analysis.

### 2. Data Modeling
* Architected a robust **Star Schema** data model connecting the Fact table (Sales/Transactions) with Dimension tables (Dates, Customers, Products, Regions).
* Established one-to-many (1:*) active relationships to ensure seamless cross-filtering and drill-down capabilities across all visuals.

### 3. Advanced DAX (Data Analysis Expressions)
Created dynamic measures to calculate complex business metrics, including:
* **Time Intelligence:** Year-to-Date (YTD) Sales, Year-over-Year (YoY) Growth, and Month-over-Month (MoM) variance.
* **Aggregations:** Profit Margins, Average Order Value (AOV), and dynamic customer ranking.

## 📂 How to Open This Project
1. Download and install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/ ) (Free).
2. Clone or download this repository to your local machine.
3. Open the `Sales_Performance_Dashboard.pbix` file in Power BI Desktop.
4. Interact with the slicers and visuals to explore the data!
