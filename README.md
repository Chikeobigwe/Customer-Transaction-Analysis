# Customer & Transaction Analysis in Power BI

## Project Overview
This project explores customer and transaction data using **Power BI** and **DAX** to derive valuable insights on customer engagement levels, churn analysis, and transaction trends. The dataset contains customer information, including **registration date, country, tiers, age, login age, and status**, as well as transaction details such as **transaction date, type, total amount, and count**.

## Key Analyses & Insights

### **1. Customer Engagement Levels**
Using **DAX**, I categorized customer engagement levels based on login age:
- **0 - 48 hours** → Frequent
- **49 - 168 hours** → Regular
- **169 - 240 hours** → Occasional
- **240+ hours** → Rare

This classification helped in understanding user activity trends and retention patterns.

### **2. Churn Analysis**
A customer was classified as **churned** if:
- **Login Age > 240 hours** AND
- **Customer Status = Blocked**

From this, I analyzed:
- **Churn rate across different tiers and countries**
- **Churn trends based on registration dates**

### **3. Customer Demographics & Distribution**
I explored:
- The **age distribution** of customers
- Engagement levels across **tiers and countries**
- Which **tiers and countries had the most customers**

### **4. Transaction Insights**
- **Transaction trends over time**: Identified peaks and dips in transaction counts and total amounts.
- **Transaction type distribution**: Analyzed how different transaction types contributed to overall activity.

## **Findings & Business Impact**
- Identified high-churn segments, helping businesses develop **targeted retention strategies**.
- Gained insights into **engagement levels** to inform customer reactivation campaigns.
- Analyzed transaction trends to determine **high-activity periods** and optimize business operations.

## **Tools Used**
- **Power BI** (Data modeling, visualization)
- **DAX** (Calculated columns, measures)
- **Excel** (Data preprocessing)

## **How to Explore the Dashboard**
- The **interactive visuals** provide insights into customer engagement, churn trends, and transaction patterns.
- Slicers allow filtering by **tiers, countries, registration date, and transaction type**.

---
This project showcases my ability to **analyze customer behavior, detect churn, and evaluate business performance through data-driven insights**. Feel free to explore the dataset and Power BI reports in the repository!


