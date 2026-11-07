# Retail-Sales-Analytics-Power-BI
An interactive Power BI dashboard to analyze retail sales, profit performance, order trends, customer behaviour, and regional insights using Power BI, DAX, Power Query, and data visualization.

  ## 1. Project Overview

An interactive Power BI dashboard project designed to analyze retail sales, profitability, customer behavior, and order trends. The project uses Power Query, DAX measures, and interactive visualizations to generate business insights and support data-driven decision-making.

## 2. Project Objectives

- Analyze overall sales and profit performance.
- Monitor key business KPIs.
- Identify high-performing regions and product categories.
- Evaluate product profitability and sales contribution.
- Understand customer segments and ordering patterns.
- Analyze monthly sales and order trends.
- Present business insights through interactive dashboards.

## 3. Tools & Technologies

- Power BI Desktop – Dashboard development and data visualization.
- Power Query – Data cleaning and transformation.
- DAX – Measures and KPI calculations.
- Microsoft Excel – Dataset handling and data review.

## 4. Dataset Overview

The project uses a retail sales dataset containing order-level business information.

| Dataset Information | Details |
|---|---|
| Total Records | 2,000 |
| Total Columns | 21 |
| Analysis Period | January 2024 – December 2025 |
| Data Type | Retail Sales Data |

**Key Dataset Fields:**

- Order ID and Order Date
- Customer ID and Customer Segment
- Region, State and City
- Product Category and Sub-Category
- Product Name and Quantity
- Sales and Profit
- Discount and Shipping Cost
- Ship Mode and Payment Mode
- Returned Status

## 5. Data Cleaning & Transformation

Data preparation was performed using Power Query before developing the dashboards.

- Reviewed column names and data types.
- Checked missing values and duplicate records.
- Used column profiling to review data quality.
- Corrected date and numerical data types.
- Verified data consistency and prepared the dataset for analysis.

## 6. Key Performance Indicators (KPIs)

- The dashboard tracks the following key metrics:
- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Average Order Value (AOV)

## 7. Key Business Questions & Findings

**Sales Performance**

1. What is the total sales revenue?

   Total sales revenue is ₹57.05M, with total profit of ₹14.55M from 2,000 orders.
 
2. Which month recorded the highest and lowest sales?

   June 2025 recorded the highest sales of ₹3.60M, while February 2024 recorded the lowest sales of ₹1.49M.

3. Which region generates the highest sales revenue?

   North leads with ₹13.51M, followed by South (₹12.89M), West (₹11.56M), East (₹9.86M), and Central (₹9.22M).

4. Which product category contributes the most to total sales?

   Technology leads with ₹34.29M (60.11%) of total sales.

5. What are the top 10 products based on sales revenue?

   External HDD (₹3.35M), Business Laptop (₹3.00M), 24-inch Monitor (₹2.86M), Student Laptop (₹2.80M), Laser Printer (₹2.57M), Inkjet Printer      (₹2.42M), 27-inch Monitor (₹2.41M), Ultrabook (₹2.39M), Budget Smartphone (₹2.16M), and External SSD (₹2.14M).

**Product & Profitability Analysis**

6. Which product generates the highest total profit?

   External HDD generates the highest profit of ₹0.85M.

7. Which category contributes the highest total profit?

   Technology generates the highest total profit of ₹8.37M, contributing 57.54% of total profit.

8. Which product category has the highest profit margin?

   Furniture has the highest profit margin at 28.25%, followed by Home & Kitchen at 27.83%.

9. What is the relationship between sales and profit?

   Sales and profit have a strong positive correlation of 0.84.

10. Which product performs best in terms of both sales and profit?
 
    External HDD leads in both sales (₹3.35M) and profit (₹0.85M).

**Customer & Order Analysis**

11. Which customer segment generates the highest number of orders?

   Consumer leads with 1,171 orders (58.55%), followed by Corporate (553) and Small Business (276).

12. How are customer segments distributed across different regions?

    Consumer leads in all five regions, with the highest count in North (274 orders), followed by West (266), South (254), East (198), and          Central (179).

13. How does monthly order volume change over time?

    March 2024 recorded the highest order volume with 102 orders, while September 2024 recorded the lowest with 69 orders.

14. Which shipping mode is used most frequently?

    Standard shipping leads with 987 orders (49.35%), followed by Express (469), Economy (388), and Same Day (156).

15. Which customer segment generates the highest sales over time?

    Consumer leads in 23 out of 24 months, reaching its highest monthly sales of ₹2.32M in June 2025.

   
## 8. **Dashboard Pages**

1. KPI Overview

Provides a high-level overview of overall business performance using key metrics such as Total Sales, Total Profit, Total Orders, Profit Margin, and Average Order Value.

2. Sales Performance

Analyzes sales trends, regional revenue, category contribution, product performance, and profitability.

3. Product & Profitability Analysis

Focuses on product-level performance, regional profitability, profit margins, and the relationship between sales and profit.

4. Customer & Order Analysis

Analyzes customer segments, category distribution, regional customer patterns, monthly order trends, shipping preferences, and segment-wise sales performance.

5. Executive Summary & Business Insights

Provides an executive-level overview using KPI cards, a Decomposition Tree, a Regional Sales & Profit Matrix, business insights, and interactive slicers.
  
## 9. Dashboard Screenshots

### 1. KPI Overview
<img width="662" height="369" alt="Screenshot 2026-11-07 043622" src="https://github.com/user-attachments/assets/65cd0890-89aa-4473-b806-c95258b9619b" />

### 2. Sales Performance
<img width="640" height="380" alt="Screenshot 2026-11-07 044103" src="https://github.com/user-attachments/assets/6e548c9b-1227-4582-b44a-aa08f506931b" />

### 3. Product & Profitability Analysis
<img width="618" height="369" alt="Screenshot 2026-11-07 044130" src="https://github.com/user-attachments/assets/d2c3c244-13c4-4868-912b-176454ded3b7" />

### 4. Customer & Order Analysis
<img width="486" height="370" alt="Screenshot 2026-11-07 044158" src="https://github.com/user-attachments/assets/65fdc8b6-11f9-45d9-a87e-8dc39a16a4e4" />

### 5. Executive Summary & Business Insights
<img width="586" height="367" alt="Screenshot 2026-11-07 044237" src="https://github.com/user-attachments/assets/b33fdee8-b8d2-4999-9bec-8f2e7af65cbf" />





**Data Cleaning & Transformation**

- Reviewed dataset structure and column data types.
- Performed data profiling to check data quality.
- Checked for missing values, errors, and duplicate records.
- Corrected data types, including date columns.
- Used Power Query for data preparation and transformation.

**Skills Demonstrated**

- Data Cleaning & Transformation
- Power Query
- DAX Measures
- KPI Development
- Data Visualization
- Business Analysis
- Sales & Profitability Analysis
- Customer Segmentation
- Interactive Dashboard Development

## 10. DAX Measures

DAX was used to create key business calculations and performance indicators.

**Total Sales**
```dax
Total Sales = SUM('Orders'[Sales (INR)])
```

**Total Profit**
```dax
Total Profit = SUM('Orders'[Profit (INR)])
```

**Total Orders**
```dax
Total Orders = DISTINCTCOUNT('Orders'[Order ID])
```

**Profit Margin %**
```dax
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
```

**Average Order Value (AOV)**
```dax
AOV = DIVIDE([Total Sales], [Total Orders], 0)
```

## 11. Interactive Dashboard Features

- **Order Date Slicer:** Filter data by a selected date range.
- **Region Slicer:** Analyse performance across individual regions.
- **Product Category Slicer:** Focus on specific product categories.
- **Interactive Visuals:** Explore data through visual interactions and cross-filtering.
- **Decomposition Tree:** Drill down into sales by region, category, customer segment, and shipping mode.

## 12. Key Business Insights & Recommendations

Based on the analysis, the following business insights were identified:

1. **Technology dominates sales:** It contributes 60.11% of total sales and 57.54% of total profit.
2. **North is the leading region:** It generates the highest regional sales revenue at ₹13.51M.
3. **Consumer is the largest segment:** It contributes 58.55% of total orders and leads monthly sales in 23 out of 24 months.
4. **Furniture has the highest profit margin:** It delivers a margin of 28.25%, despite Technology generating the highest total profit.
5. **External HDD is a top performer:** It ranks first in both total sales and total profit.

### Business Recommendations

- Focus on maintaining and growing the Technology category's sales performance.
- Investigate opportunities to improve sales in the Central region.
- Analyse the factors contributing to Furniture's higher profit margin.
- Develop customer retention strategies for the Consumer segment.
- Review product-level profitability to identify further growth opportunities.

## 13. Skills Demonstrated

- Data Cleaning & Transformation
- Power Query
- Data Analysis
- DAX Measures
- KPI Development
- Data Visualization
- Interactive Dashboard Development
- Business Intelligence
- Sales & Profitability Analysis
- Business Insights & Reporting

## 14. Project Conclusion

This project demonstrates the use of Power BI to transform retail sales data into meaningful business insights. Through data preparation, DAX calculations, interactive dashboards, and business analysis, the project identifies key sales drivers, profitable categories, customer trends, and regional performance.

The dashboard provides a consolidated view of business performance and supports data-driven decision-making.
