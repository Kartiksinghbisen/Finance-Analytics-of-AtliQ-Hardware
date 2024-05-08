# Finance-Analytics-of-AtliQ-Hardware

Welcome to the AtliQ Hardware Data Analytics Project Repository. In this project, I have used MySQL to generate insightful reports.

## Problem Statement

AtliQ Hardware is a company that sells computer hardware to clients which has several branches throughout India. AtliQ Hardware emerged as the first indigenous manufacturer of computer peripherals in India. As a result, their sales and revenue increased every year. As the size of Excel files continues to grow, it is encountering performance issues, causing them to become unresponsive and stop working. To address this challenge AtliQ Hardware hired aa team of data analysts who will use MySQL as their database management system and to extract valuable insights from the data. These insights will empower our company to make more informed and strategic decisions, ultimately optimizing our operations and performance.

## Business Terminology

1. Fiscal Year
2. Gross Price
3. Gross Price Total

   
## Insights

1. # Product Sales Report

![Screenshot 2024-05-08 101307](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/d2ad7e7f-5e18-468f-a09c-963dfbf95b36)



I created two user-defined functions get_fiscal_year and get_fiscal_year_quarter.
I used JOIN to get the report.

![Screenshot 2024-05-08 101332](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/bd7c7edb-b716-46bb-9b25-d9b0aa8539de)


I generated a report for product sales for Croma India customers for fiscal_year = 2021
This report will help in tracking individual product sales and help in analysing products.

![Screenshot 2024-05-08 101350](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/343def7a-2ac0-4d1e-8865-8b426ea95862)

[croma__2021_all_trans (1).csv](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/files/15243960/croma__2021_all_trans.1.csv)

2. ## Gross Monthly Total Sales Report


![Screenshot 2024-05-08 101407](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/ef5ec376-7347-4883-b6b0-b2cdae6776a8)

Performed aggregate function (SUM) to calculate gross_price_total
Joined two tables fact_sales_monthly and fact_gross_price.

![Screenshot 2024-05-08 101422](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/1fa75060-431e-49ad-a3d2-cf69e49920b2)

I generated a report for gross_price_total.

![Screenshot 2024-05-08 101443](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/c406c93d-81a2-4cbb-bc54-95b22e973997)


[monthly_sales.csv](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/files/15243969/monthly_sales.csv)



3. # Yearly Sales Report

![Screenshot 2024-05-08 101500](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/89f6effa-9e1a-467a-aef8-3fee2a2ce4aa)

Retrieved fiscal_year using user-defined function get_fiscal_year.
Calculated yearly_sales using an aggregate function(SUM).
Joined two tables fact_sales_monthly and fact_gross_price.\

![Screenshot 2024-05-08 101519](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/76f7caf9-5c09-4b8e-baa2-ea3572d91e55)


I Generated a report for Croma India.
In the fiscal year 2022 Croma India has the highest sales.
![Screenshot 2024-05-08 101531](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/assets/139736045/8d3481d2-80ea-4622-9d33-586fd5de4f75)

[yearly_sales.csv](https://github.com/Kartiksinghbisen/Finance-Analytics-of-AtliQ-Hardware/files/15243971/yearly_sales.csv)
