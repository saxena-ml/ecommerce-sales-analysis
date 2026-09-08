# Blinkit Sales Performance Analysis

## 📊 Project Overview

This project analyzes **Blinkit sales performance data** using Microsoft Excel. The objective is to transform raw order and product data into meaningful sales insights through data preparation, analysis, pivot tables, and an interactive dashboard.

The project demonstrates an end-to-end Excel data analysis workflow:

**Raw Data → Data Preparation → Analysis → Pivot Tables → Dashboard**

## 🛠️ Tools & Skills

* Microsoft Excel
* Data Cleaning & Preparation
* Excel Formulas
* Data Transformation
* Pivot Tables
* Data Analysis
* Dashboard Development
* KPI Analysis
* Data Visualization

## 📁 Dataset Structure

The workbook contains the following six sheets:

### 1. Orders

Contains order-level information including:

* Order ID
* Customer ID
* Order Date
* Promised Delivery Time
* Actual Delivery Time
* Delivery Status
* Payment Method
* Delivery Partner ID
* Store ID

### 2. Order_items

Contains product-level information associated with each order:

* Order ID
* Product ID
* Quantity
* Unit Price
* Sales

Sales is calculated using:

`Quantity × Unit Price`

### 3. Products

Contains product master data including:

* Product ID
* Product Name
* Category
* Brand
* Price
* MRP
* Margin Percentage
* Shelf Life
* Minimum Stock Level
* Maximum Stock Level

### 4. Data Analysis

This sheet combines useful information from the **Orders, Order_items, and Products** sheets to create a consolidated dataset for analysis.

Additional fields were created for:

* Order Year
* Order Month

This consolidated dataset was used as the primary source for the dashboard analysis.

### 5. Pivot Tables

Pivot tables were created to analyze key sales dimensions, including:

* Sales by Month
* Sales by Category
* Top 10 Products
* Sales by Brand
* Payment Method
* Other sales performance breakdowns

### 6. Dashboard

The final dashboard provides a visual summary of Blinkit's sales performance.

Key KPIs include:

* **Total Sales**
* **Total Orders**
* **Total Quantity**
* **Average Order Value**

The dashboard also presents sales trends and product/category/brand performance through charts and visualizations.

## 📈 Key Analysis Areas

The project focuses on answering questions such as:

* How are sales changing over time?
* Which categories generate the most sales?
* Which products are the top performers?
* Which brands contribute most to sales?
* Which payment methods are commonly used?
* What is the average order value?
* How does order quantity contribute to overall sales?

## 🔄 Analysis Workflow

Orders + Order_items + Products  →  Data Analysis  →  Pivot Tables  →  Dashboard

## 🎯 Project Objective

The main objective of this project is to demonstrate how Excel can be used to convert multiple related datasets into a structured analytical report and dashboard that can support business decision-making.


## 📂 Files

* `Blinkit Sales Performance.xlsx` — Complete Excel workbook containing all six analysis sheets.
* `Dashboard.png` — Dashboard preview.
* `README.md` — Project documentation.

## 💡 Skills Demonstrated

**Excel | Data Analysis | Data Preparation | Pivot Tables | Dashboard Development | KPI Analysis | Data Visualization**
