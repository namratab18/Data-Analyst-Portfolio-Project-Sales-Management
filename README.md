# 📊 Sales Management – Data Analyst Portfolio Project

## 📝 Project Overview
This project is a Data Analytics portfolio case study focused on **Sales Management**. The goal is to extract meaningful insights from raw sales data using **SQL**. It demonstrates data cleaning, querying, and analysis to support decision-making in a business context.

---

## 🎯 Objective
To analyze and manage sales performance using SQL by answering key business questions such as:
- Which products are top-performing?
- Which regions generate the most revenue?
- What are the sales trends over time?
- Who are the top sales representatives?

---

## 🛠️ Tools & Technologies
- **SQL** (MySQL / PostgreSQL)
- **Excel** (for initial data cleaning)
- **Power BI / Tableau** ( for dashboard visualization)*
- **GitHub** *(for version control and project sharing)*

---

## 📂 Dataset
The dataset includes fields such as:
- `Order ID`
- `Date`
- `Product`
- `Category`
- `Region`
- `Salesperson`
- `Quantity`
- `Unit Price`
- `Total Amount`



---

## 🔍 Key Analyses Performed
- Monthly and yearly sales trends
- Product-wise and category-wise sales performance
- Regional sales comparison
- Salesperson performance analysis
- KPIs such as:
  - Total Revenue
  - Average Order Value
  - Units Sold
  - Customer Count (if available)

---

## 📌 Sample SQL Query
```sql
SELECT 
  region, 
  SUM(total_amount) AS total_sales
FROM 
  sales_data
GROUP BY 
  region
ORDER BY 
  total_sales DESC;
