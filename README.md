# 🛒 Retail Sales Analysis (End-to-End Project)

## 📌 Project Overview
This project is an **end-to-end Retail Sales Analysis** designed to solve real-world business problems using historical transaction data.  
The analysis covers **data cleaning, transformation, exploratory data analysis (EDA), SQL integration, and interactive dashboarding** to generate actionable business insights.

The goal is to help retail stakeholders understand **revenue drivers, customer behavior, discount impact, and sales trends** for data-driven decision-making.

---

## 🧠 Business Problem
Retail businesses generate large volumes of transaction data across multiple product categories, locations, payment methods, and discount strategies.  
However, without a centralized analytical view, stakeholders struggle to:

- Identify top revenue-generating products and categories  
- Understand customer purchasing behavior  
- Evaluate the effectiveness of discounts  
- Track time-based sales trends  

This project analyzes retail sales data to uncover actionable insights that support **pricing, promotion, and sales strategy decisions**.

---

## 🎯 Key Business Questions
- Which products and categories generate the highest revenue?
- How do discounts impact quantity sold and total revenue?
- Which payment methods are most preferred by customers?
- How do online and in-store sales compare?
- What are the monthly, yearly, and weekly sales trends?
- Who are the top revenue-generating customers?

---

## 🔄 Project Workflow
**Business Problem → Raw Data → EDA & ETL (Python) → SQL (MySQL) → Power BI Dashboard**

---

## 📁 Repository Structure

| File Name                     | Description                                                      |
| ----------------------------- | ---------------------------------------------------------------- |
| `Business_Problem.docx`         | Retail business problem statement and analytical objectives      |
| `retail_store_sales.csv`      | Raw retail transaction-level dataset                             |
| `EDA.ipynb`                   | Python notebook for data cleaning, ETL, and exploratory analysis |
| `EDA_Report.pdf`              | PDF report summarizing EDA insights                              |
| `Retail_Sales_Dashboard.pbix` | Interactive Power BI dashboard file                              |
| `Retail_Sales_Dashboard.png`  | Dashboard preview image                                          |
| `README.md`                   | Project documentation and overview                               |



---

## 🧪 Dataset Details
- **Total Transactions:** 12,575  
- **Time Period:** 2022 – 2025  
- **Total Items:** 200  
- **Key Columns:**  
  Transaction ID, Customer ID, Category, Item, Price per Unit, Quantity,  
  Total Spent, Payment Method, Location, Transaction Date, Discount Applied  

---

## ⚙️ EDA & ETL Highlights
- Handled missing values using statistical and logical imputation
- Standardized column names and data types
- Converted transaction date to datetime format
- Identified and validated outliers
- Loaded cleaned data into **MySQL** using SQLAlchemy
- Performed exploratory analysis to identify patterns and trends

---

## 📊 Dashboard Highlights (Power BI)
- **KPIs:** Total Revenue, YTD Revenue, Total Quantity Sold, Transactions, Items
- Revenue by location (Online vs In-store)
- Revenue by payment method
- Top 5 items by revenue
- Discount impact on quantity sold
- Monthly, yearly, and weekly revenue trends
- Customer-wise revenue and payment behavior analysis

---

## 💡 Key Insights
- Revenue is almost evenly split between **online and in-store** sales, with online slightly higher
- **Cash** remains the most used payment method despite digital options
- A small number of products contribute a large share of total revenue
- Discounts help increase quantity sold
- **January and Fridays** record the highest revenue
- A few high-value customers contribute significantly to total revenue

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **SQL:** MySQL  
- **Visualization:** Power BI  
- **Others:** Jupyter Notebook, GitHub  

---

## 🧾 Conclusion
This project demonstrates the complete analytics lifecycle — from raw data to business insights — and showcases practical skills in **data analysis, ETL, SQL, and dashboarding**.  
It is a **self-driven project** designed to mirror real-world retail analytics use cases.

---

⭐ If you find this project useful, feel free to star the repository!

