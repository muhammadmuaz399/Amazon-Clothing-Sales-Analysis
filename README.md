# 📊 Amazon Clothing Sales Analysis – Power BI Project

## 📌 Project Overview

This project focuses on analyzing **Amazon clothing sales data** using **Microsoft Power BI** to uncover meaningful insights into sales performance, customer behavior, product performance, discount strategies, review ratings, and delivery performance.

The dataset contains **20,000+ clothing sales records**, covering **Men’s, Women’s, Kids’, and Baby** categories. Each record represents a unique product order by a unique customer and includes product information, pricing, discounts, customer demographics, payment methods, ratings, delivery times, regions, and device usage.

The project demonstrates an end-to-end **data analytics and business intelligence workflow**, including data cleaning, transformation, data modeling, DAX, interactive visualizations, and dashboard development.

---

## 🎯 Business Objectives

The primary goal of this project is to build an **interactive Power BI dashboard** that enables business stakeholders to:

* Understand overall sales performance
* Evaluate discount strategies
* Analyze customer review ratings
* Evaluate delivery performance
* Understand customer purchasing behavior
* Analyze sales by age group and region
* Compare device usage patterns
* Identify high-performing products, brands, and categories
* Generate actionable business insights

---

## 📂 Dataset

### Dataset Characteristics

* **Source:** Amazon clothing sales dataset
* **Records:** 20,000+
* **Industry:** E-commerce / Clothing
* **Categories:** Men, Women, Kids, Baby
* **Currency:** USD
* **Geography:** United States
* **Data Type:** Product, sales, customer, review, delivery, and transaction data

The dataset includes product attributes, pricing and discount information, customer demographics, purchasing details, and device usage information.

### 📋 Key Columns

| Column               | Description                     |
| -------------------- | ------------------------------- |
| `order_id`           | Unique Amazon-style order ID    |
| `customer_id`        | Unique customer reference       |
| `product_id`         | Product identifier              |
| `product_name`       | Product brand and title         |
| `main_category`      | Main clothing category          |
| `sub_category`       | Specific clothing item type     |
| `brand`              | Product brand                   |
| `price`              | Unit price in USD               |
| `quantity`           | Quantity purchased              |
| `discount_percent`   | Discount offered                |
| `final_price`        | Final amount paid for the order |
| `payment_method`     | Payment method used             |
| `review_rating`      | Customer rating from 1–5        |
| `order_date`         | Purchase date                   |
| `delivery_days`      | Delivery time in days           |
| `region`             | US delivery region              |
| `customer_age_group` | Customer age category           |
| `Device_Type`        | Device used for the order       |

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculated columns
* **Data Modeling**
* **Star Schema**
* **Calendar Table**
* **Interactive Visualizations**
* **Slicers & Filters**

---

# ⚙️ Project Workflow

## 1. 🔄 Data Transformation & Cleaning

The first stage involved checking and preparing the dataset before analysis.

### Data Cleaning Tasks

* Check data quality
* Identify valid, error, and empty values
* Remove blank rows and columns where applicable
* Handle missing values using appropriate techniques such as:

  * Mean
  * Median
  * Mode
* Remove duplicate records where applicable
* Prepare the dataset for analysis

---

## 2. 🧩 Data Modeling

A structured data model was developed in Power BI to support efficient analysis.

### Data Modeling Tasks

* Create a **Calendar Table using DAX**
* Add a **weekday column**
* Build a **Star Schema**
* Establish relationships between the Amazon Sales table and Calendar table

### 📐 Model Structure

**Amazon Sales Fact Table**

* Orders
* Products
* Customers
* Revenue
* Quantity
* Discounts
* Ratings
* Delivery information

⬇️

**Calendar Dimension**

* Date
* Month
* Year
* Week
* Weekday

---

# 📊 Dashboard & Data Analysis

The Power BI report is designed around three major analytical areas.

---

## 📈 Page 1 – Sales Overview

The Sales Overview page focuses on understanding the overall performance of the business.

### Key Analysis

* Total Orders
* Total Revenue
* Average Order Value
* Total Products
* Average Rating
* Monthly and weekly sales/revenue trends
* Sales performance by main category
* Revenue contribution by region
* Payment method distribution
* Most frequently used payment method

A narrative summary is also included to communicate the major findings from the analysis.

### 📌 Key KPIs

* **Total Orders**
* **Total Revenue**
* **Average Order Value**
* **Total Products**
* **Average Rating**

---

## 👕 Page 2 – Product, Category & Brand Analysis

This page examines product and category-level performance.

### Key Analysis

* Top-selling brands by revenue
* Sub-categories with the highest quantity sold
* Best and worst performing sub-categories based on average rating
* Main category performance across different age groups
* Brand-level performance comparison

### 📋 Brand Summary

A summary table provides:

* Total Orders
* Revenue
* Average Rating
* Total Customer Count

---

## 🚚 Page 3 – Review & Delivery Insights

The third page focuses on customer behavior, reviews, devices, and delivery performance.

### Key Analysis

* Orders by device type
* Review performance by age group
* Device preferences across different age groups
* Delivery performance
* Revenue by region

### 🚦 Delivery Classification

Delivery days are categorized into three groups:

| Delivery Days | Delivery Type |
| ------------: | ------------- |
|      0–2 Days | Fast          |
|      3–5 Days | Medium        |
|       >5 Days | Slow          |

The analysis identifies the most common delivery type and evaluates regional revenue performance using a map visualization.

---

# 🎛️ Interactive Slicers & Filters

The dashboard includes interactive filters that allow users to dynamically explore the data.

### Available Slicers

* 📅 Date Range
* 👕 Main Category
* 🌎 Region
* 🏷️ Brand
* 👥 Age Group

These filters allow stakeholders to drill down into specific customer segments, products, time periods, and regions.

---

# 📊 Visualizations

Each dashboard page contains multiple visuals designed to communicate business insights clearly.

Potential visualizations include:

* KPI Cards
* Line Charts
* Bar/Column Charts
* Donut/Pie Charts
* Tables
* Matrix Visuals
* Map Charts
* Trend Analysis
* Category Comparisons
* Brand Performance Charts

The project brief requires **at least five visuals on each page**.

---

# 🎨 Dashboard Design Principles

The dashboard follows professional data visualization practices:

* Consistent visual sizing
* Proper alignment
* Adequate white space
* Meaningful chart titles
* Readable fonts and labels
* Highlighting of best/worst performers
* Appropriate data labels
* Minimal unnecessary elements
* Clean and professional layout
* Easy interpretation at first glance

---

# 💡 Key Business Questions

The project addresses questions such as:

### Sales Performance

* What is the total revenue?
* How many orders were placed?
* What is the average order value?
* How does revenue change over time?
* Which categories generate the most sales?
* Which regions contribute the most revenue?

### Product & Brand Performance

* Which brands generate the highest revenue?
* Which sub-categories sell the highest quantity?
* Which sub-category has the best average rating?
* Which sub-category has the lowest average rating?
* How do categories perform across different age groups?

### Customer Behavior

* Which age groups provide better product ratings?
* Which devices are most commonly used?
* Which devices are preferred by different age groups?
* How does customer behavior vary across regions?

### Delivery Performance

* What proportion of orders are Fast, Medium, or Slow?
* Which delivery type is most common?
* Which regions generate the highest revenue?

---

# 📈 Key Outcomes

Through this project, the following analytics capabilities are demonstrated:

* End-to-end Power BI dashboard development
* Data cleaning and transformation
* Missing-value and duplicate handling
* DAX-based calendar table creation
* Star-schema data modeling
* KPI development
* Sales trend analysis
* Product and brand analysis
* Customer segmentation
* Review analysis
* Delivery performance analysis
* Geographic revenue analysis
* Interactive dashboard development

---

# 📦 Deliverable

The final project is delivered as a:

**Power BI `.pbix` file**

---

# 🚀 How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Navigate through the dashboard pages.
4. Use the slicers to filter the analysis.
5. Explore sales, product, customer, review, and delivery insights.
6. Interact with the visualizations to investigate different business segments.

---

# 👨‍💻 Author

**Muhammad Muaz**

---

## ⭐ Project Highlights

> **Amazon Clothing Sales Analysis** is an interactive Power BI business intelligence project that transforms 20,000+ clothing sales records into an analytical dashboard for understanding **sales performance, product and brand performance, customer behavior, reviews, discounts, delivery, and regional revenue**.
