# Tableau Sales Dashboard Project

##  Project Overview
This project is an interactive Tableau dashboard built to analyze sales performance, profit trends, and key business KPIs using a retail dataset.  
The dashboard helps identify trends over time, compare performance metrics, and support data-driven decision making.

---

## Dataset Description
The dataset contains retail transaction data with the following key columns:

- Order Date
- Sales
- Quantity
- Discount
- Profit
- Category 
- Region
---

## Data Cleaning & Preparation

Before building the dashboard, the dataset was cleaned and prepared:

### 1. Handling Missing Values
- Checked for null or missing values in all columns
- Removed or replaced missing entries where necessary

### 2. Data Type Correction
- Converted **Order Date** to Date format
- Ensured numerical fields (Sales, Profit, Quantity, Discount) are in correct numeric format

### 3. Duplicate Removal
- Removed duplicate rows to avoid inflated metrics

### 4. Feature Engineering
- Created calculated fields:
  - **Profit Margin = Profit / Sales**

### 5. Data Consistency
- Standardized categorical values (e.g., Region, Category names)
- Verified consistency in date ranges and numerical values

---

## Dashboard Features

The Tableau dashboard includes:

###  KPI Section (Top Panel)
- Total Sales → `SUM(Sales)`
- Total Profit → `SUM(Profit)`
- Percentage of Profit Margin 

---

### Trend Analysis (Middle Panel)

- Sales Trend over time
- Profit Trend over time
- Time-based analysis using Month-Year hierarchy

---

### Category & Performance Insights (Bottom Panel)
- Sales by Category 
- Profit distribution across segments
- Optional filters (Region, Category, Time)

---


