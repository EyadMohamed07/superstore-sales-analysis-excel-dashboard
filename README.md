# Superstore Sales Analysis & Excel Dashboard

## Overview

This project is a sales analysis and dashboard built in Microsoft Excel using the Superstore dataset.

The main goal was to turn the raw transaction data into a clear dashboard that can be used to understand sales, profit, customers, products, regions, shipping, and returned orders.

The project includes the original data, data analysis, calculations, PivotTables, and the final dashboard.

## Dataset

The dataset contains **9,994 transaction rows** and **5,009 unique orders** from **793 customers**.

Each row represents a transaction/product line, so one order can appear in multiple rows.

The dataset includes information about:

* Order and shipping dates
* Customers
* Customer segments
* Products
* Categories and sub-categories
* Cities, states, and regions
* Sales
* Quantity
* Discount
* Profit
* COGS
* Shipping mode
* Shipping duration
* Returned orders

## Business Questions

The analysis was built around a few practical business questions:

* How much sales and profit did the business generate?
* Which categories and products generate the most sales?
* Which customers contribute the most revenue?
* Which states and cities have the highest sales?
* How are sales distributed across regions and customer segments?
* Which shipping methods are used the most?
* How long does each shipping method take on average?
* How much sales come from returned orders?
* How did sales change over the years?

## Tools Used

* Microsoft Excel
* PivotTables
* PivotCharts
* Excel formulas
* Data analysis
* KPI calculations
* Data visualization
* Dashboard design

## Project Structure

### `Row_Data.xlsx`

The original dataset before the analysis.

### `Full_project.xlsx`

The completed Excel project containing the calculations, PivotTables, analysis, and dashboard.

## Main Sheets

### Orders

Contains the main transaction-level data used throughout the project.

### People

Contains sales person and regional information.

### Return

Contains returned order information used to analyze the effect of returns on sales.

### Calculation

Contains the main analysis and PivotTables, including:

* Sales by customer
* Order count by shipping mode
* Sales by category and segment
* Top customers
* Sales by city
* Shipping duration analysis

### Shipping Cost

Contains shipping cost information by state.

### Dash Calculation

Contains the calculations used to build the dashboard KPIs and charts.

### WireFrame

Used for the dashboard layout/planning.

## Key KPIs

| KPI                     |        Result |
| ----------------------- | ------------: |
| Total Sales             | $2,297,200.86 |
| Total Profit            |   $286,397.02 |
| Profit Margin           |        12.47% |
| Total Orders            |         5,009 |
| Total Customers         |           793 |
| Profit per Order        |        $57.18 |
| Returned Sales          |   $180,504.28 |
| Net Sales after Returns | $2,116,696.58 |

## Key Findings

### Sales & Profit

The business generated approximately **$2.30M in sales** and **$286.4K in profit**, giving an overall profit margin of about **12.47%**.

There are 9,994 transaction rows but only 5,009 unique orders, which shows that individual orders can contain multiple products.

### Category Performance

Technology was the highest-selling category with approximately **$836K in sales**.

The other two categories were:

* Furniture — approximately **$742K**
* Office Supplies — approximately **$719K**

Technology generated the largest share of total sales.

### Geographic Performance

California was the highest-selling state with approximately **$457.7K in sales**.

At the city level, **New York City** generated approximately **$256.4K**, making it the highest-selling city in the analysis.

The dashboard also provides a comparison of sales across the Central, East, South, and West regions.

### Customer Performance

The analysis includes **793 customers** and identifies the customers with the highest sales contribution.

A separate analysis was also used to compare customer segments across product categories.

### Shipping

Standard Class was the most frequently used shipping method, accounting for **5,968 transaction rows**.

The average shipping duration across all orders was approximately **3.96 days**.

Average shipping duration by shipping mode:

* First Class — 2.18 days
* Second Class — 3.24 days
* Standard Class — 5.01 days
* Same Day — less than 1 day

### Returns

Returned orders generated approximately **$180.5K in sales**, representing around **7.86% of total sales**.

After removing returned sales, net sales were approximately **$2.12M**.

The project includes a dedicated analysis of returned vs. non-returned orders.

### Yearly Sales

Sales were analyzed across the four years in the dataset.

The highest annual sales were recorded in **2017**, with approximately **$733.2K** in sales.

## Dashboard

The final dashboard brings the main KPIs and analysis together in one place.

It provides a quick view of:

* Sales
* Profit
* COGS
* Returns
* Category performance
* Geographic performance
* Customer performance
* Shipping performance
* Yearly sales trends

### Dashboard Preview

Add the dashboard screenshot here:

<img width="1387" height="653" alt="image" src="https://github.com/user-attachments/assets/befd3511-e7e3-40e4-809f-cca60633a560" />


## What I Practiced

This project helped me practice working with a complete business dataset rather than only creating individual Excel charts.

The main focus was on:

* Understanding and cleaning raw data
* Creating useful calculated fields
* Building PivotTables
* Creating PivotCharts
* Designing KPIs
* Analyzing sales and profitability
* Comparing customer and product performance
* Analyzing returns and shipping
* Turning the analysis into an interactive dashboard

## Conclusion

This project demonstrates how Excel can be used to move from raw transaction data to a complete sales analysis and dashboard.

The final result combines data analysis, business metrics, visualizations, and a dashboard that can be used to explore different aspects of sales performance.

## Files

* `Row_Data.xlsx` — Original dataset
* `Full_project.xlsx` — Final Excel project

## Author

**[Eyad Mohamed]**

Data Analyst | Excel | Data Analysis | Business Intelligence

---

If you found this project useful, feel free to explore the files and connect with me.
