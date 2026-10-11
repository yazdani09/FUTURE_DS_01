## Project Overview

This project analyzes retail sales data to understand business performance, identify sales trends, compare regional and product category performance, and investigate products with low or negative profit.

I completed this project using Python in VS Code with a Jupyter Notebook. The analysis helped me practice data cleaning, exploratory data analysis, business KPI calculations, and data visualization.

## Project Objectives

* Analyze overall sales and profit.
* Identify the best-performing regions and product categories.
* Examine monthly sales trends from 2014 to 2017.
* Identify the top 10 products by sales.
* Investigate products with the lowest total profit.
* Present business findings through charts and recommendations.

## Tools and Technologies

* **Python** — analysis and calculations
* **Pandas** — data loading, inspection, grouping, and aggregation
* **Matplotlib** — data visualization
* **Jupyter Notebook** — writing and running analysis code
* **VS Code** — project development environment

## Dataset

The project uses the Sample Superstore dataset, containing 9,994 records and 21 columns.

Important fields include Order Date, Region, Category, Sub-Category, Product Name, Sales, Quantity, Discount, and Profit.

The dataset covers orders from January 2014 to December 2017.

## Key Findings

* **Total sales:** $2,297,200.86
* **Total profit:** $286,397.02
* **Overall profit margin:** 12.47%
* **Unique orders:** 5,009
* **Unique customers:** 793
* The West region generated the highest sales and total profit.
* Technology generated the highest sales and profit among the three product categories.
* Furniture had a comparatively low profit margin of approximately 2.49%.
* Several products recorded negative total profit and require further investigation.

## Analysis and Visualizations

The project includes:

* Sales performance by region
* Profit comparison by product category
* Monthly sales trend
* Top 10 products by sales
* Products with the lowest total profit

## Data Quality Checks

The initial data-quality checks found no missing values or exact duplicate rows. Additional checks found no negative or zero sales, negative quantities, negative discounts, discounts above 100%, or shipping dates earlier than order dates.

## Business Recommendations

1. Investigate the low profit margin in the Furniture category.
2. Review discounts, pricing, and costs for loss-making products.
3. Study the Central region's lower profit margin.
4. Monitor sales and profit together to measure business performance.
5. Review monthly trends regularly to identify changes in performance.

## Project Structure

```text
FUTURE_DS_01/
├── dataset/
│   └── Sample - Superstore.csv.xlsx
├── output/
│   ├── sales_by_region.png
│   ├── profit_by_category.png
│   ├── monthly_sales_trend.png
│   ├── top_10_products_chart.png
│   ├── top_products_sales_comparison.png
│   ├── loss_making_products_chart.png
│   └── CSV analysis tables
├── sales_analysis.ipynb
├── Business_Sales_Analysis_Report.docx
├── README.md
└── .gitignore
```

## Conclusion

This project gave me practical experience in analyzing business data with Python and presenting the results through visualizations. The findings highlight differences in regional performance, product category profitability, and product-level losses. The analysis can help guide further investigation and support better-informed business decisions.