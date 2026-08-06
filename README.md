# 📊 Sales & Shipping Performance Analysis Dashboard

An interactive **Power BI dashboard** developed to analyze sales performance, customer segments, product performance, regional sales, and shipping efficiency.

## 🛠️ Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Visualization
- CSV Dataset

## 📌 Project Overview

This project analyzes sales and shipping data to identify important business trends and provide actionable insights through an interactive Power BI dashboard.

The dashboard is divided into two main sections:

### 1. Sales Performance Dashboard

The sales dashboard provides an overview of:

- Total Sales
- Total Orders
- Total Customers
- Average Shipping Days
- Sales trends by year
- Sales by category
- Sales by region
- Sales by customer segment
- Top 10 products by sales

### 2. Shipping & Delivery Analysis

The shipping dashboard focuses on:

- Average shipping days
- Orders by shipping mode
- Average shipping time by shipping mode
- Average shipping time by region
- Interactive filtering using Year, Region, Ship Mode, and Segment

## 📈 Key DAX Measures

### Total Sales

```DAX
Total Sales = SUM(cleaned_sales[Sales])
