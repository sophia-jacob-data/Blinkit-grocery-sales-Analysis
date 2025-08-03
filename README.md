# Blinkit Grocery Sales Analysis

## Project Summary

This project explores grocery retail performance for a simulated delivery company **Blinkit** with the goal of uncovering key business insights across product types, customer segments, and outlet channels. Using Power BI, Excel, and Power Query, I analyzed over 8,000 item-level sales records to support data-driven decisions around inventory, pricing, and product visibility.

The final dashboard empowers stakeholders to monitor product trends, outlet performance, and profit contributors in real-time.

---

## Business Goals

- Identify top-performing product categories and subcategories
- Evaluate the impact of outlet type and location on sales
- Understand how product attributes (e.g., fat content, visibility) affect profitability
- Assist in inventory optimization and pricing strategies

---

## Dataset Overview

- **Total Records:** 8,523 transactions  
- **Source Format:** Excel (.xlsx)  
- **Dimensions:** Product ID, Product Category, Product Type, Fat Content, Visibility, MRP, Outlet Type, Outlet Size, City Tier, Years in Operation, and Sales  
- **Data Type:** Historical transactional sales data

---

## Business Questions Answered

1. Which product categories and types generate the highest revenue?
2. How does product visibility correlate with sales and profit margin?
3. What role do outlet types and city tiers play in sales performance?
4. Are low-fat or high-fat products more profitable across cities?
5. How should inventory be prioritized for each location?

---

## Data Cleaning & Preparation

Performed in **Power Query (Power BI)** and Excel:
- Replaced blank and missing values in `Outlet Size` and `Outlet Type`
- Standardized inconsistent text formatting (e.g., “low fat” vs. “Low Fat”)
- Resolved discrepancies in `Item_Type` and `Product_Category`
- Converted visibility and MRP fields to numeric types for analysis
- Created DAX measures to calculate:
  - Total Revenue
  - Average MRP
  - Contribution to Total Sales by Product Category and Outlet

---

## Tools & Technologies Used

- **Power BI** – for dashboard development, DAX measures, slicers, and report visuals  
- **Power Query** – for data transformation and cleaning  
- **Excel** – initial data exploration and formatting  
- **DAX** – to calculate KPIs, percentages, and aggregations

---

## Key Insights

- **Top Revenue Contributors:** Snack Foods, Dairy, and Fruits & Vegetables  
- **Outlet Type Impact:** Supermarkets Type1 and Grocery Stores had the highest sales volume, but not necessarily the highest revenue per unit  
- **Product Visibility:** High-visibility items had stronger sales performance in Tier 1 cities; low-visibility products underperformed regardless of MRP  
- **Fat Content:** Low Fat products made up over 60% of sales, but High Fat products yielded slightly higher average revenue per item  
- **Inventory Optimization:** Certain outlet types in Tier 2 cities consistently understock high-performing categories, indicating potential revenue loss  

---

## Dashboard Preview

*(Insert your Power BI dashboard screenshot here)*  
`Screenshot 2025-07-13 002645.png`
`Screenshot 2025-07-13 005149.png`

---

## Files Included

- `BlinkIT Grocery Data.xlsx` – Cleaned transactional dataset  
- `Blinkit Project.pbix` – Full Power BI dashboard  
- `README.md` – This documentation file

---

## Project Links

- **Portfolio Page:** [sophiajacob.my.canva.site](https://sophiajacob.my.canva.site)  
- **LinkedIn:** [linkedin.com/in/sophia-jacob-](https://linkedin.com/in/sophia-jacob-)

---

## Author

**Sophia Jacob**  
Data Analyst | Power BI • SQL • Excel • Python  
Email: sophiajacob753@gmail.com  

---

## Notes

This project simulates a real-world retail business environment to demonstrate core data analysis competencies in business intelligence, data visualization, and insight storytelling.
