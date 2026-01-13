Vendor Performance Analysis
🔹 Project Overview

This project analyzes vendor-level purchase, sales, and profitability data to identify loss-making vendors, capital blocked in inventory, and high-performing vendors.
The objective is to deliver clear, data-driven recommendations for inventory optimization and vendor management that can directly improve business profitability and cash flow.

This project focuses on decision-making, not just reporting numbers.

🔹 Problem Statement

Despite strong overall sales, the business experiences significant losses and inventory inefficiencies caused by:

Over-purchasing from low-performing vendors

Poor alignment between purchase volume and actual sales demand

Products and brands operating at low or negative profit margins

The core challenge is to determine:

Where money is being lost

Why it is happening

What corrective actions should be taken

🔹 Dataset Summary

Level of analysis: Vendor-wise

Key metrics used:

Total Purchase

Total Sales

Gross Profit

Profit Margin

Stock Turnover

Derived fields:

Vendor Category (4-category segmentation)

Recommendation (action-oriented)

🔹 Tools & Technologies

Python (Pandas, NumPy) – data cleaning, aggregation, feature engineering

SQL (MySQL) – data storage and querying

Power BI – KPI reporting and interactive dashboard

🔹 Methodology

Loaded and cleaned raw transactional data

Aggregated metrics at the vendor level

Created business KPIs for sales, profit, and inventory risk

Segmented vendors into four performance-based categories

Built a Power BI dashboard to support business decisions

🔹 Vendor Categorization Logic

Vendors were classified into four categories using profitability and inventory movement metrics:

Category 1: High Profit & Fast-Moving
Vendors with strong profitability and healthy inventory turnover

Category 2: Profitable but Slow-Moving
Vendors that generate profit but suffer from slow inventory movement

Category 3: Sold but Loss-Making
Vendors that generate sales but still incur losses due to pricing or cost issues

Category 4: Unsold Inventory
Vendors where purchases were made but sales did not occur, leading to capital blockage

Each category was assigned a clear and actionable business recommendation.

🔹 Key Dashboard KPIs

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/5dbdeae7d02b7248f96afea62f577e4194f4685d/Screenshot%20(189).png)

Total Sales ($) – measures overall revenue generated

Total Gross Profit ($) – indicates overall business profitability

Inventory at Risk ($) – highlights money blocked in unsold inventory

Loss-Making Vendors (%) – shows how widespread vendor-level losses are

Insight:
While total sales are strong, profit and inventory efficiency KPIs reveal structural inefficiencies in vendor and inventory management.

🔹 Key Visualizations & Insights
📊 Total Purchase vs Total Sales

This chart compares overall purchase spending with sales revenue.

Insight:
Purchase spending is not always justified by sales performance, indicating over-purchasing and inefficient demand planning.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(180).png)

📊 Top 10 Vendors by Sales

Shows vendors contributing the highest revenue.

Insight:
Sales are highly concentrated among a few vendors, but high sales do not automatically translate into high profit.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(181).png)

📊 Top 10 Vendors by Profit

Ranks vendors based on actual profit contribution.

Insight:
Profit concentration is narrower than sales concentration, highlighting that only a small subset of vendors truly drive profitability.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(182).png)

📊 Distribution of Profit Margin

Displays how profit margins are spread across vendors/products.

Insight:
A large number of products operate at low or near-zero margins, increasing business risk and sensitivity to cost fluctuations.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(183).png)

📊 Loss-Making vs Profitable Products

Compares the count of profitable and loss-making products.

Insight:
Loss-making products represent a significant drag on overall profitability and require immediate review.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(184).png)

📊 Brand Pricing vs Profitability

Analyzes the relationship between pricing and profit.

Insight:
Higher pricing does not guarantee higher profit, indicating pricing inefficiencies or weak demand for premium brands.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(186).png)

📊 Profit Margin by Top Vendors

Compares efficiency among major vendors.

Insight:
Some high-volume vendors operate at very low margins, suggesting high procurement, freight, or tax costs.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(187).png)

📊 Top 10 Vendors: Purchase vs Sales

Compares purchase investment against sales performance.

Insight:
Certain vendors show high purchase volumes with weak sales, leading to inventory imbalance and capital blockage.

![image alt](https://github.com/nikhil3156/vendor-performance-analysis/blob/d28a548370fcd94642ec15f8cf322a82d67af458/Screenshot%20(188).png)

🔹 Key Insights (Recruiter-Focused)

High sales volume alone is a misleading performance metric

Profit is driven by a small group of efficient vendors

Significant capital is locked in unsold or slow-moving inventory

Inventory inefficiency contributes more to losses than pricing alone

Vendor-level monitoring is critical for profitability control

🔹 Business Recommendations

Increase purchases from vendors with strong profit and healthy turnover

Closely monitor and optimize vendors that are profitable but slow-moving

Renegotiate pricing, costs, or discontinue consistently loss-making vendors

Immediately stop purchasing from vendors with unsold inventory

Implement minimum profit margin thresholds (e.g., 10–15%)

Shift purchasing decisions from sales-based to profit-based evaluation

🔹 Conclusion

This project demonstrates how vendor-level data can be transformed into actionable business decisions rather than static reports.
The analysis reveals that the primary challenge is not insufficient sales, but inefficient inventory allocation and poor vendor prioritization.

By applying data-driven vendor segmentation and profitability analysis, the business can:

Reduce losses

Free blocked capital

Improve inventory efficiency

Achieve sustainable profitability

The Power BI dashboard serves as a single source of truth for continuously monitoring vendor performance and guiding strategic purchasing decisions.
