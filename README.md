# E-Commerce Sales Analytics Dashboard

## Project Overview

An interactive Power BI dashboard that analyzes sales performance, customer behavior, regional performance, payment methods, delivery performance, and revenue trends on **5,000 e-commerce orders**.

It was built as part of my data analytics portfolio to turn raw transaction data into insights that support business decisions.

## Business Questions

- What is the overall revenue and order performance?
- Which product categories generate the most revenue?
- Which regions perform best?
- How does revenue change over time?
- Which payment methods are used most?
- How many customers are repeat customers?
- What is the average customer rating?
- How does delivery performance vary?
- How does current revenue compare with the previous year?

## Key Insights

- Total revenue reached **5.11M** across 5,000 orders.
- **Electronics** is the top category, generating **1.8M**, about 35% of total revenue.
- The **West** region leads all regions in revenue.
- **Card** is the most used payment method.
- Revenue grew **6.87%** compared with the previous year.

## Dashboard Pages

1. **Executive Overview:** revenue, orders, customers, quantity, average order value, and average rating, with revenue trend, category, region, and payment method views.
2. **Sales Analysis:** revenue over time, by category and region, quantity vs revenue, growth, and top-performing categories.
3. **Customer & Operations Analysis:** customers by region, revenue by payment method, ratings, delivery performance, category vs region, and repeat vs one-time customers.
4. **Advanced Analytics:** actual vs previous year revenue, growth %, dynamic KPI selection, dynamic Top N, and dynamic titles.

## Tools & Technologies

Power BI, DAX, Power Query, Data Modeling

## Key DAX Measures

```DAX
Total Revenue = SUM(Sales[revenue])
```

```DAX
Total Orders = DISTINCTCOUNT(Sales[order_id])
```

```DAX
Total Customers = DISTINCTCOUNT(Sales[customer_id])
```

```DAX
Average Order Value = DIVIDE([Total Revenue], [Total Orders])
```

```DAX
Revenue Growth % = DIVIDE([Total Revenue] - [Revenue PY], [Revenue PY])
```

## Interactive Features

Filters by year, month, product category, region, and date range, plus dynamic KPIs, time-based analysis, and drill-through.

## Author

**Ibrahim Harbi**, aspiring marketing data analyst
GitHub: [eng-heema](https://github.com/eng-heema)
