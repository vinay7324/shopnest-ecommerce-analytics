# ShopNest E-Commerce Analytics Dashboard

![Power BI](https://img.shields.io/badge/PowerBI-Data%20Visualization-yellow)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Business%20Insights-blue)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-green)
![Ecommerce](https://img.shields.io/badge/Ecommerce-Analytics-orange)

---

## Project Overview

This project analyzes **ShopNest E-commerce data** using **Microsoft Power BI** to uncover insights related to sales performance, delivery efficiency, customer satisfaction, payment behavior, and regional sales trends.

The dashboard integrates multiple datasets and visualizations into a **single interactive executive dashboard** that enables stakeholders to monitor performance and make **data-driven decisions**.

---

## Business Problem

E-commerce companies generate large volumes of transactional data related to **orders, payments, product categories, deliveries, and customer reviews**.

However, without proper analysis, it becomes difficult to answer key business questions such as:

- Which product categories generate the highest revenue?
- Are delivery delays affecting certain product categories?
- Which payment methods do customers prefer?
- How satisfied are customers with their orders?
- Which regions generate the most revenue?
- Are there seasonal trends in sales?

This dashboard solves these problems by converting raw transactional data into **interactive visual insights**.

---

## Dataset Description

The ShopNest dataset contains multiple tables representing different aspects of the e-commerce business.

### Orders Dataset

Contains information about:

- Order ID  
- Purchase timestamp  
- Estimated delivery date  
- Actual delivery date  
- Customer ID  

This dataset helps analyze **delivery performance and order timelines**.

---

### Order Items Dataset

Contains:

- Order ID  
- Product ID  
- Price  
- Freight value  

Used to calculate **total revenue and product sales performance**.

---

### Products Dataset

Contains:

- Product ID  
- Product category  

Used to analyze **category-wise sales performance**.

---

### Payments Dataset

Contains:

- Order ID  
- Payment type  
- Payment value  

Used to analyze **customer payment behavior**.

---

### Reviews Dataset

Contains:

- Review score  
- Order ID  
- Review comments  

Used to evaluate **customer satisfaction**.

---

### Customers Dataset

Contains:

- Customer ID  
- Customer state  
- Customer location  

Used for **regional sales analysis**.

---

## Data Preparation (Power Query)

Before creating the dashboard, the data was cleaned and transformed using **Power Query Editor**.

### Data Cleaning

The following preprocessing steps were performed:

- Removed unnecessary columns  
- Checked for missing values  
- Standardized column names  
- Converted data types (dates, numbers)

---

## Dashboard Visualizations

The dashboard contains several analytical visuals designed to answer key business questions.

---

### 1. Top Categories by Total Revenue

**Visualization:** Bar Chart  

**Purpose:**  
Identify the **top 10 product categories generating the highest revenue**.

**How it was built:**

- Axis → Product Category  
- Values → Total Revenue  
- Sorted in descending order  

**Business Value:**  
Helps management focus on **high-performing product segments**.

---

### 2. Delayed Orders Analysis (By Category)

**Visualization:** Clustered Column Chart  

**Purpose:**  
Identify which product categories experience the **most delivery delays**.

**How it was built:**

- Axis → Product Category  
- Values → Delayed Orders  

**Business Value:**  
Highlights potential **logistics or supplier issues**.

---

### 3. Monthly Delayed vs On-Time Orders

**Visualization:** Stacked Column Chart  

**Purpose:**  
Compare **delivery performance month by month**.

**How it was built:**

- Axis → Month  
- Values → Delayed Orders & On-Time Orders  

**Business Value:**  
Reveals **delivery efficiency trends over time**.

---

### 4. Payment Method Analysis

**Visualization:** Donut Chart  

**Purpose:**  
Identify **customer payment preferences**.

**Categories include:**

- Credit Card  
- Boleto  
- Voucher  

**Business Value:**  
Helps optimize **payment gateway partnerships**.

---

### 5. Customer Satisfaction Analysis

**Visualization:** Bar Chart  

**Purpose:**  
Identify **top 10 highest-rated orders** and **bottom 10 lowest-rated orders**.

**How it was built:**

- Axis → Order ID  
- Values → Review Score  

**Business Value:**  
Helps understand **customer satisfaction patterns**.

---

### 6. State-Wise Sales Analysis

**Visualization:** Filled Map  

**Purpose:**  
Analyze **revenue distribution across different states**.

**How it was built:**

- Location → Customer State  
- Values → Total Revenue  

**Business Value:**  
Identifies **high-performing geographic markets**.

---

### 7. Seasonal Sales Patterns

**Visualization:** Line Chart  

**Purpose:**  
Understand **quarterly seasonal sales trends**.

**How it was built:**

- Axis → Quarter  
- Values → Total Revenue  

**Business Value:**  
Helps plan **inventory and marketing campaigns**.

---

### 8. Yearly Revenue Trend

**Visualization:** Line Chart  

**Purpose:**  
Track **overall business growth over time**.

**How it was built:**

- Axis → Year  
- Values → Total Revenue  

**Business Value:**  
Shows **long-term business growth trends**.

---

## Key Insights

From the analysis:

- Certain product categories dominate **total revenue**
- **Credit card payments** are the most frequently used
- Delivery delays vary significantly by **product category**
- Some states contribute disproportionately to **total sales**
- Sales exhibit **seasonal peaks across quarters**

---

## Tools Used

- Microsoft Power BI  
- Power Query  
- DAX  
- Data Modeling  
- Data Visualization  

---

## Author

**Vinay Giri**  

Aspiring Data Analyst  
Power BI | SQL | Python | Data Visualization
