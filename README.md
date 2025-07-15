# AtliQ Hardware Insights Using MySQL

## Problem Statement  
AtliQ Hardware is a fast-growing consumer electronics company. However, their reporting was entirely Excel-based, making it inefficient and error-prone.  
To improve business analytics and decision-making, the company transitioned to using SQL for reliable, scalable, and automated reporting.

---

## Project Overview  
This project explores AtliQ Hardware’s finance analytics data using MySQL. The objective is to automate recurring and ad-hoc business reports by leveraging SQL functions, views, procedures, and window functions.

---

## Key Highlights

- Created user-defined functions for calculating fiscal year and quarter  
- Developed stored procedures to automate:
  - Monthly sales reports  
  - Market badge logic (Gold if quantity > 5M, else Silver)  
  - Top 5 markets, customers, and products by net sales  
- Built SQL views for:
  - Pre-invoice and post-invoice deductions  
  - Final net sales  
- Used window functions to generate a report showing:
  - Top 10 markets by percentage net sales for FY 2021

---

## Concepts & Skills Used

- Subqueries  
- Common Table Expressions (CTEs)  
- Views  
- Stored Procedures  
- Window Functions (ROW_NUMBER, RANK, DENSE_RANK)  
- User-Defined Functions (UDFs)

---

## Attached Screenshots

| No. | Screenshot Description | Preview |
|-----|------------------------|---------|
| 01 | Fiscal Year Function | ![Fiscal Year](./Screenshots/01_fiscal_year_function.png) |
| 02 | Fiscal Quarter Function | ![Fiscal Quarter](./Screenshots/02_fiscal_quarter_function.png) |
| 03 | Monthly Sales Report (Procedure) | ![Monthly Sales](./Screenshots/03_monthly_sales_report_procedure.png) |
| 04 | Market Badge Procedure | ![Market Badge](./Screenshots/04_market_badge_procedure.png) |
| 05 | View: Pre-Invoice Discount | ![Pre Invoice](./Screenshots/05_view_pre_invoice_discount.png) |
| 06 | View: Post-Invoice Discount | ![Post Invoice](./Screenshots/06_view_post_invoice_discount.png) |
| 07 | View: Net Sales | ![Net Sales](./Screenshots/07_view_net_sales.png) |
| 08 | Top 5 Customers Procedure | ![Top Customers](./Screenshots/08_top5_customers_procedure.png) |
| 09 | Top 5 Markets Procedure | ![Top Markets](./Screenshots/09_top5_markets_procedure.png) |
| 10 | Top 5 Products Procedure | ![Top Products](./Screenshots/10_top5_products_procedure.png) |
| 11 | Percentage Net Sales by Market (Bar Chart) | ![Net Sales Chart](./Screenshots/11_top10_markets_percent_net_sales_chart.png) |

---
