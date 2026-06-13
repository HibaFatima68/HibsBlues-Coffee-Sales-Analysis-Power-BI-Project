# 🐻 HibsBlues Coffee – Sales Analysis

##  Project Overview
This project analyzes coffee shop sales data from Kaggle (March 2024 – March 2025) to understand customer behavior, product performance, and revenue trends.

The dataset contains **3,547 transactions** across multiple coffee products and provides insights into time-based and product-based sales patterns.

---

## Problem Statement
A coffee shop business wants to improve profitability and operational efficiency but lacks clarity on:
- Peak sales hours
- Best-performing products
- Revenue trends over time
- Customer purchasing behavior

This project aims to analyze sales data and provide actionable business insights.

---

## Dataset Information

- Source: Kaggle Coffee Shop Sales Dataset  
- Time Period: March 2024 – March 2025  
- Total Records: 3,547  
- Total Features: 11  
- Products: 8 coffee types  

### Key Columns:
- Date  
- Time  
- Hour of Day  
- Coffee Name  
- Revenue (Money)  
- Payment Method  
- Time of Day  
- Weekday  
- Month  

---

## Data Processing

- Dataset was clean and structured  
- Minimal preprocessing required  
- Feature engineering applied:
  - Hour of day categorization  
  - Time of day grouping  
  - Weekday and month sorting  

---

## Data Model

### Fact Table: Sales Transactions
**Measures:**
- Revenue  
- Transaction Count  
- Average Order Value  

### Dimensions:
- Product (coffee_name)  
- Time (Date, Hour, Time of Day)  
- Weekday  
- Month  
- Payment Method  

---

## Dashboard Overview (Power BI)

### Page 1: Overview
- Total Revenue KPI  
- Total Transactions KPI  
- Average Order Value KPI  
- Product Performance Analysis  
- Payment Method Distribution
  
<img width="975" height="565" alt="image" src="https://github.com/user-attachments/assets/7d772a65-7c3d-4bf9-bb4b-b0938a1133f4" />


### Page 2: Time Analysis
- Hourly sales trends  
- Weekday performance  
- Time-of-day breakdown

<img width="975" height="562" alt="image" src="https://github.com/user-attachments/assets/04bb6b52-66b3-4563-99e4-f87f0b8e614a" />


### Page 3: Product Analysis
- Coffee popularity  
- Revenue contribution per product  
- Payment behavior trends  
<img width="975" height="540" alt="image" src="https://github.com/user-attachments/assets/35e252d9-80ad-42a6-a44c-cd48a541180c" />

### Page 4–5: Advanced Insights
- Decomposition tree for revenue breakdown  
- Scatter plot analysis (price vs time behavior)  
- Weekday vs product analysis

<img width="975" height="528" alt="image" src="https://github.com/user-attachments/assets/e8b787cc-50c6-472f-be2f-b322f8e6e75f" />


---

## Key Insights

- 10 AM is the peak sales hour  
- Latte is the top-selling product  
- Afternoon shows highest sales activity  
- Tuesdays perform best among weekdays  
- Espresso underperforms  
- Card payments dominate cash transactions  
- Sales fluctuate based on time and weekday patterns  

---

## Recommendations

- Increase staff during peak hours (9–11 AM, 3–5 PM)  
- Promote low-performing products like Espresso  
- Introduce weekend promotions and loyalty programs  
- Bundle low-selling products with high-performing items  
- Run targeted campaigns during low-performing periods  

---

## Key Learnings

- Data cleaning and transformation  
- Power BI dashboard development  
- Business intelligence storytelling  
- Fact & dimension modeling  
- Converting raw data into actionable insights  

---

## Tools Used
- Power BI  
- Excel  
- Kaggle Dataset  

---

## Conclusion
This project helped transform raw transactional data into meaningful insights that can support better decision-making in a retail coffee business.

---
