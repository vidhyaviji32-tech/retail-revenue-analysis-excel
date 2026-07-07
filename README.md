# Retail Revenue Analysis for Leadership Decision Making

## Project Overview
B&J Biscuit Company retail transaction data analysis using Microsoft Excel to support leadership decision making through data cleaning, calculated metrics, and an interactive dashboard.

## Dataset Overview
- Total Records: 12,000 transactions
- Year: 2024
- Cities: 9 locations
- Products: 10 biscuit brands
- Sales Representatives: 8
- Payment Methods: Cash, Credit Card, Debit Card, Mobile Payment
- Tool Used: Microsoft Excel

## Tasks Completed

### Task 1: Data Cleaning
Buyer Name column had First Name, Last Name and Location joined together with special characters and extra spaces. Used LEFT, MID, FIND, TRIM, CLEAN and PROPER formulas along with Flash Fill to clean and separate the data.

### Task 2: XLOOKUP Mapping
Transaction data had only Product Code. Used XLOOKUP to fetch Biscuit Brand, Unit Price and Cost Price from the Products sheet.

### Task 3: Calculation Columns
Calculated Total Revenue, Total Cost, Profit, Profit Margin percentage and Age Group using formulas based on Quantity, Price and Cost columns.

### Task 4 and 5: Product Insights and Customer Demographics
Created Pivot Tables to identify best and worst performing products, and which age group and gender purchases the most.

### Task 6: Sales Representative KPIs
Created Pivot Table with Sales Representative names, Revenue and Profit Margin to identify top performers.

### Task 7 and 8: Location KPIs and Payment Analysis
Extracted Location from Buyer Name column and analyzed revenue by city and by payment method.

### Task 9: Visual Analysis
Created 7 charts including bar charts, donut chart, scatter plots, line chart and heatmap to visualize product revenue, gender sales, age group revenue, unit price vs profit, and monthly revenue trends.

### Task 10: Interactive Dashboard
Combined all KPIs and charts into a single Dashboard sheet with Slicers for Product, Gender, Age Group, Location, Sales Representative and a Timeline filter for Transaction Date.

## Excel Functions and Features Used
- LEFT, MID, FIND, TRIM, CLEAN, PROPER for data cleaning
- Flash Fill for splitting names
- XLOOKUP for mapping product details
- IFERROR for handling calculation errors
- Nested IF for Age Group classification
- Pivot Tables and Pivot Charts
- Conditional Formatting with Color Scale
- Slicers and Timeline for interactive filtering

## Key Insights
- Clear revenue and profit patterns identified across products, cities and sales representatives
- Age group and gender based purchase patterns identified
- Interactive dashboard enables leadership to filter and analyze data in real time

## Files in this Repository
- Full project presentation PDF

**Presented by:** Vidhya M
