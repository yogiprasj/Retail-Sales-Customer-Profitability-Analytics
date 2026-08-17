# Retail Sales, Customer & Profitability Analytics

An end-to-end retail data analytics project using Python and Power BI to analyze sales performance, profitability, product performance, customer segments, and product returns.

## Project Overview

This project analyzes retail transaction data to generate business insights through data preparation, exploratory data analysis, KPI analysis, and interactive Power BI dashboards.

The project focuses on four main analytical areas:

- Sales Performance
- Product & Profitability Performance
- Customer Analysis
- Return Analysis

The analysis was performed using Python for data preparation and exploratory analysis, while Power BI was used to build the interactive business intelligence dashboard.

## Business Objectives

This project aims to answer several key business questions:

- How does revenue and gross profit change over time?
- Which product categories generate the highest revenue?
- Which products generate the highest revenue and profit?
- Which regions contribute the most revenue?
- How does sales volume relate to profitability?
- How does discounting relate to profit margin?
- Which customer segments have higher return rates?
- Which product categories experience the most returns?
- What are the most common reasons for product returns?

## Dataset

The dataset used in this project is the **Retail Data** dataset obtained from Kaggle.

**Raw Dataset Source:**

https://www.kaggle.com/datasets/hyerdrac/retail-data

The original dataset consists of retail transaction data covering customers, products, categories, orders, and order details.

The raw data was processed and transformed into an analytical dataset before being used for dashboard development.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- DAX

## Project Files

### `Retail_Data_Analysis.ipynb`

Jupyter Notebook containing the data analysis workflow, including:

- Data loading
- Data understanding
- Data quality checking
- Missing-value analysis
- Duplicate checking
- Data validation
- Data transformation
- Data integration
- Exploratory data analysis
- KPI calculation
- Analytical dataset preparation

### `retail_analytical_dataset.csv`

The processed analytical dataset used as the primary data source for the Power BI dashboard.

The dataset contains information related to:

- Orders
- Customers
- Products
- Product categories
- Quantity
- Sales
- Discounts
- Costs
- Profit
- Returns
- Return reasons

### `Retail Business Dashboard.pbix`

Power BI dashboard containing three analytical pages designed to provide an interactive overview of retail business performance.

## Power BI Dashboard

### Page 1 — Executive Overview

Provides a high-level overview of the overall business performance.

**Key KPIs:**

- Total Revenue: **$728.47K**
- Gross Profit: **$202.20K**
- Profit Margin: **27.76%**
- Return Rate: **4.70%**

**Visualizations:**

- Revenue & Gross Profit Trend
- Revenue by Product Category
- Revenue by Region
- Return Rate by Category

**Main findings:**

- Meat & Poultry generated the highest revenue among product categories.
- Marmara generated the highest revenue among the analyzed regions.
- Revenue and gross profit fluctuate throughout the year, with May showing one of the strongest monthly performances.
- Household Cleaning recorded the highest return rate among the categories displayed.

---

### Page 2 — Sales & Product Performance

Focuses on product-level sales performance, sales volume, pricing, discounts, and profitability.

**Key KPIs:**

- Total Quantity Sold: **77K**
- Average Order Value: **$72.85**
- Average Selling Price: **$9.42**
- Discount Rate: **3.79%**

**Visualizations:**

- Top 10 Products by Revenue
- Top 10 Products by Profit
- Sales Volume vs Profitability by Category
- Discount Rate vs Profit Margin by Category

**Main findings:**

- ABC's Ground Beef was the top-performing product by both revenue and profit among the Top 10 products.
- Several products combine high sales volume with strong profitability, indicating their importance to overall business performance.
- Product categories show different relationships between sales volume and gross profit.
- Higher discount rates do not necessarily result in higher profitability, indicating the importance of controlling discount levels.

---

### Page 3 — Return & Customer Analysis

Focuses on customer return behavior, return trends, and return reasons.

**Key KPIs:**

- Return Rate: **4.70%**
- Returned Items: **1K**
- Returned Revenue: **$33.48K**
- Returned Profit: **$9.42K**

**Visualizations:**

- Returned Items by Category
- Return Rate Trend by Month
- Return Rate by Customer Segment
- Returned Items by Reason

**Main findings:**

- Beverages recorded the highest number of returned items among the categories displayed.
- Return rates fluctuate throughout the year, with the highest levels occurring around March and October.
- Return rates across VIP, Premium, and Standard customer segments are relatively similar.
- Customer Changed Mind was the most common return reason, followed by Expired Date and Wrong Item Sent.

## Key Business Insights

### Sales Performance

- Total revenue reached **$728.47K**, supported by **$202.20K** in gross profit.
- The overall profit margin was **27.76%**.
- Meat & Poultry was the strongest revenue-generating category.
- Marmara was the strongest revenue-generating region.

### Product Performance

- ABC's Ground Beef ranked first among the analyzed products in both revenue and gross profit.
- Product performance varies considerably across categories in terms of sales volume and profitability.
- Revenue alone should not be used to evaluate product performance because profitability and sales volume provide additional business context.

### Pricing & Discount

- The overall discount rate was **3.79%**.
- The relationship between discount rate and profit margin differs across categories.
- Excessive discounting can reduce profitability and should therefore be evaluated alongside product margins.

### Returns

- The overall return rate was **4.70%**.
- Beverages generated the highest returned-item volume among the displayed categories.
- Customer Changed Mind was the dominant return reason.
- Return rates were relatively consistent across customer segments.

## Data-Driven Recommendations

1. **Prioritize high-performing products**

   Maintain product availability and promotional visibility for products that consistently generate high revenue and profit, particularly ABC's Ground Beef.

2. **Optimize discount strategies**

   Evaluate discount levels based on their impact on profit margin rather than focusing only on sales volume. High discounts should be applied selectively to avoid unnecessary margin erosion.

3. **Investigate high-return categories**

   Analyze products within high-return categories such as Beverages to identify recurring product, packaging, quality, or customer-expectation issues.

4. **Reduce preventable returns**

   Since Customer Changed Mind is the most common return reason, improve product descriptions, specifications, images, and customer information to help customers make more informed purchasing decisions.

5. **Investigate operational return issues**

   Return reasons such as Wrong Item Sent indicate potential fulfillment or warehouse issues. Order-picking and fulfillment processes should be reviewed to reduce preventable returns.

6. **Monitor regional performance**

   The strong revenue contribution from Marmara indicates an opportunity to investigate the factors behind its performance and identify whether similar strategies can be applied to lower-performing regions.

7. **Evaluate profitability alongside revenue**

   Business decisions should consider revenue, sales volume, profit, and profit margin simultaneously to avoid prioritizing products that generate high sales but relatively weak profitability.

