# E-Commerce Sales Analytics Dashboard — Power BI

##  Project Overview

This project presents an interactive **E-Commerce Sales Analytics Dashboard** built using **Microsoft Power BI**.

The goal of this project is to analyze sales performance, customer behavior, regional performance, payment methods, delivery performance, and revenue trends through interactive and dynamic visualizations.

The dashboard is designed to transform raw e-commerce transaction data into meaningful business insights that can support data-driven decision-making.

---

##  Business Objectives

The dashboard answers key business questions such as:

* What is the overall revenue and order performance?
* Which product categories generate the most revenue?
* Which regions perform best?
* How does revenue change over time?
* Which payment methods are most frequently used?
* How many customers are repeat customers?
* What is the average customer rating?
* How does delivery performance vary?
* How does current revenue compare with the previous year?

---

##  Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of the business performance.

**Key KPIs:**

* Total Revenue
* Total Orders
* Total Customers
* Total Quantity
* Average Order Value
* Average Customer Rating

**Analysis:**

* Revenue Trend
* Revenue by Category
* Revenue by Region
* Orders by Payment Method
* Interactive Filters

---

### 2. Sales Analysis

Focuses on sales performance and revenue trends.

**Analysis includes:**

* Revenue over time
* Revenue by Product Category
* Revenue by Region
* Quantity vs Revenue
* Revenue Growth
* Top-performing categories

---

### 3. Customer & Operations Analysis

Analyzes customer behavior and operational performance.

**Analysis includes:**

* Customer distribution by region
* Revenue by payment method
* Customer ratings
* Delivery performance
* Category vs Region analysis
* Repeat vs One-Time Customers

---

### 4. Advanced Analytics

Provides deeper analytical insights using DAX and Power BI features.

**Features include:**

* Actual vs Previous Year Revenue
* Revenue Growth %
* Dynamic KPI Selection
* Dynamic Top N Analysis
* Dynamic Titles
* Interactive filtering

---

##  Tools & Technologies

* **Power BI**
* **DAX**
* **Power Query**
* **Data Modeling**
* **Data Visualization**

---

##  Dataset

The dataset contains **5,000 e-commerce orders** with information related to:

* Order Date
* Customer ID
* Product Category
* Region
* Quantity
* Unit Price
* Discount
* Payment Method
* Delivery Days
* Customer Rating
* Revenue

---

##  Key DAX Measures

Some of the main measures created in this project include:

```DAX
Total Revenue =
SUM(Sales[revenue])
```

```DAX
Total Orders =
DISTINCTCOUNT(Sales[order_id])
```

```DAX
Total Customers =
DISTINCTCOUNT(Sales[customer_id])
```

```DAX
Average Order Value =
DIVIDE(
    [Total Revenue],
    [Total Orders]
)
```

```DAX
Revenue Growth % =
DIVIDE(
    [Total Revenue] - [Revenue PY],
    [Revenue PY]
)
```

---

##  Interactive Features

The dashboard includes interactive filters that allow users to explore the data by:

* Year
* Month
* Product Category
* Region
* Date Range

The dashboard also includes dynamic KPIs, time-based analysis, and drill-through functionality.

---

##  Key Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX
* Time Intelligence
* KPI Development
* Interactive Dashboard Design
* Business Analysis
* Data Visualization

---

##  Repository Structure

```text
E-Commerce-Sales-Analytics-PowerBI/
│
├── E-Commerce-Sales-Analytics.pbix
├── ecommerce_sales_analytics_5000.csv
├── Dashboard.pdf
└── README.md
```

---

##  Author

**Ibrahim Harbi**

Data Analyst | Power BI | SQL | Excel | Python

---

##  Project Purpose

This project was created as part of my **Data Analytics Portfolio** to demonstrate my ability to transform raw data into interactive dashboards and actionable business insights using Power BI.
