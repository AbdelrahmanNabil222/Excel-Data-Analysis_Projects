# Adidas US Sales Analysis (Excel)

An interactive Excel dashboard analyzing Adidas US sales across retailers, regions, states, products, and sales channels, to understand where revenue and profit are coming from.

![Dashboard](dashboard.png)

## Business Problem
Adidas sells through multiple retailers and channels across the US. Management needs clear answers to:
- How have sales and profit changed over time?
- Which states, regions, and retailers drive the most revenue?
- Which products and sales channels are the most profitable?

## Dataset
- **Source:** Adidas US Sales dataset (public)
- **Size:** 9,648 transactions, 12 columns
- **Period:** January 2020 to December 2021
- **Coverage:** 6 retailers, 5 regions, 50 states, 52 cities, 6 product categories, 3 sales methods
- **Columns:** Retailer, Retailer ID, Invoice Date, Region, State, City, Product, Price per Unit, Units Sold, Total Sales, Operating Profit, Sales Method

## Tools
Microsoft Excel: Pivot Tables, Pivot Charts, Slicers, Data Cleaning, Dashboard Design

## Process
1. **Data cleaning:** checked for missing values and duplicates (none found) and fixed an inconsistent category label (`Men's aparel` corrected to `Men's Apparel`).
2. **Analysis:** built pivot tables for sales by year/month, state, product, and sales method.
3. **KPIs:** Total Sales and Total Operating Profit.
4. **Dashboard:** combined the pivot charts into one interactive dashboard with slicers for filtering.

## Key Insights

| KPI | Value |
|-----|-------|
| Total Sales | **$89.99M** |
| Total Operating Profit | **$33.21M** |
| Overall Profit Margin | **36.9%** |
| Units Sold | **2.48M** |

1. **Massive growth in 2021:** sales grew from $18.2M in 2020 to $71.8M in 2021, almost 4x. Peak months were July ($7.8M) and December ($7.8M) 2021.
2. **Top states:** New York ($6.4M), California ($6.0M), and Florida ($5.9M) lead in sales, followed by Texas ($4.6M). Nebraska is the lowest at $0.6M.
3. **The West region leads in sales** ($27.0M, 30% of total) **but has the lowest margin** (33.2%), while the South has the highest margin (42.3%).
4. **Footwear dominates:** footwear is about 66% of total sales. Men's Street Footwear is the best seller ($20.9M) and also one of the most profitable (39.7% margin).
5. **Channels:** In-store brings the most revenue ($35.7M), but **Online has the highest margin (39.0%)**, which makes it the most efficient channel.
6. **Retailers:** West Gear ($24.3M) and Foot Locker ($22.0M) are the biggest partners, while Sports Direct has the best profit margin (40.7%).

## Recommendations
- Invest more in the **online channel**, since it has the highest margin and room to grow.
- Review pricing and costs in the **West region** to improve its margin.
- Focus inventory and promotions on **Men's Street Footwear** and **Women's Apparel**.
- Strengthen the relationship with **Sports Direct**, which converts sales to profit most efficiently.

## Files
- `Adidas_US_Sales_Datasets_analysis.xlsx`: the full workbook (Data, Pivot tables, Dashboard)
- `dashboard.png`: dashboard screenshot
