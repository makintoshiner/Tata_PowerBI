# 🛍️ Online Retail Sales Analysis

## 📌 Project Overview

This project aims to analyze online retail transaction data to provide actionable business insights to the company’s leadership. Built in Power BI, the report includes analysis of revenue, sales volume, geographic demand, and customer performance.

The main objective is to visualize key metrics that help the CEO and CMO make strategic decisions regarding business growth, sales forecasting, and customer focus.

## 📊 Dataset and Data Preparation

The dataset contains historical transaction records from an online retail store. Key fields include:

- `InvoiceNo`: Invoice number  
- `StockCode`: Product code  
- `Description`: Product description  
- `Quantity`: Number of items sold  
- `InvoiceDate`: Date of purchase  
- `UnitPrice`: Price per unit  
- `CustomerID`: Customer identifier  
- `Country`: Country of the buyer  

### 📦 Additional Transformations

- Created a new calculated column:  
  ```DAX
  Revenue = Quantity * UnitPrice

- Removed rows where:
- `Quantity < 1` (product returns)
- `UnitPrice < 0` (data entry errors)

Data cleaning was performed using **Power Query**.

---

## 🧠 Business Questions & Visualizations

This report addresses four key business questions:

### 1. Revenue Trends in 2011
Analyze monthly revenue in 2011 to identify seasonal trends and support future sales planning.

### 2. Top 10 Countries by Revenue (excluding UK)
Visualize top countries by total revenue and sales volume. The United Kingdom is excluded from the analysis.

### 3. Top 10 Customers by Revenue
Display top revenue-generating customers in descending order. Useful for loyalty and retention strategies.

### 4. Demand by Country (excluding UK)
A heatmap showing demand by country. The goal is to identify potential regions for international expansion.

---

## 🧰 Technologies Used

- **Power BI Desktop** – for data modeling and dashboard development  
- **Power Query** – for data transformation and cleaning  
- **DAX** – for calculated fields and KPIs  

---

## 🖼️ Screenshots

![image](https://github.com/user-attachments/assets/c358da68-31bc-4f3e-8688-7b93d78e6691)
![image](https://github.com/user-attachments/assets/e1fa03b8-43c8-451c-aa69-a962c1665585)
![image](https://github.com/user-attachments/assets/5623e440-eb58-40b2-a1c8-a28513adf06b)
![image](https://github.com/user-attachments/assets/d5dbdb70-9aae-4080-8f84-13aae1c08d6e)

---

## 🌐 View Dashboard

🔗 [Click here to view the live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDcxMTAwNTAtMTJhMS00YmY4LTlkNjctYWU3MzQwMDMzMjkxIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)
