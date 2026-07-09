Sales Performance Analysis Dashboard
Project Overview

A business analytics project focused on analyzing global retail sales performance, identifying profitability drivers, and providing actionable recommendations using Python and Power BI.

The objective was to understand:

Which markets generate the most revenue and profit
Which products drive business performance
How discounts affect profitability
Which areas provide opportunities for improvement
Business Problem

A retail company wants to improve decision-making by understanding sales trends, customer behavior, and factors affecting profitability.

The company needs answers to questions such as:

Which markets perform best?
Which products generate the most value?
Are discounts increasing sales or reducing profit?
How can profitability be improved?
Dataset

The dataset contains:

51,290 sales transactions
Multiple countries and markets
Product categories and sub-categories
Customer segments
Sales, profit, discount, and shipping information

Main features:

| Category             | Columns                                    |
| -------------------- | ------------------------------------------ |
| Order Information    | order_id, order_date, ship_date, ship_mode |
| Customer Information | customer_name, segment                     |
| Product Information  | category, sub_category, product_name       |
| Financial Metrics    | sales, profit, discount                    |
| Logistics            | shipping_cost, shipping_days               |


Tools Used
Data Analysis
Python
Pandas
NumPy
Matplotlib
Seaborn
Business Intelligence
Power BI
DAX
Other
Excel
GitHub
Data Cleaning & Preparation

The following steps were performed:

Converted date columns into datetime format
Converted sales values into numeric format
Checked missing values
Validated data types
Created new feature:

Shipping Days

to measure delivery time.

Key Performance Indicators

The dashboard tracks:

| KPI                 |   Value |
| ------------------- | ------: |
| Total Sales         | $12.64M |
| Total Profit        |  $1.47M |
| Profit Margin       |  11.62% |
| Orders              |  25,035 |
| Customers           |     795 |
| Average Order Value |    $505 |



Dashboard Pages
1. Executive Overview

Includes:

Sales performance KPIs
Monthly sales trend
Sales by market
Profit by category

Screenshot:

2. Product & Customer Analysis

Includes:

Top products by sales
Top products by profit
Customer segment analysis
Shipping mode analysis

Screenshot:

3. Profitability Analysis

Includes:

Profit margin by market
Discount impact analysis
Discount vs profit margin
Shipping cost vs profit

Screenshot:

Key Business Insights
1. Discount Strategy

High discounts negatively affect profitability.

Discounts above 40% frequently resulted in negative profit.

Recommendation:

Implement targeted discount strategies based on product profitability.

2. Market Performance

APAC generated the highest revenue and profit.

Canada achieved the highest profit margin despite lower sales volume.

Recommendation:

Study successful strategies in high-margin markets.

3. Category Performance

Technology generated the highest profit.

Furniture had lower profit margins compared with other categories.

Recommendation:

Review pricing and cost structure for lower-margin categories.

4. Product Performance

Some products generated high revenue but lower profitability.

Recommendation:

Focus on products that balance sales volume and profit contribution.

Recommendations
Reduce excessive discounts that damage margins.
Focus on high-profit products and categories.
Investigate low-margin markets and products.
Optimize shipping costs for lower-profit transactions.
Use dashboard monitoring for continuous performance tracking.



Project Files

Sales-Performance-Analysis/

├── data/
│   └── sales_cleaned_final.csv

├── notebooks/
│   └── sales_analysis.ipynb

├── powerbi/
│   └── Sales_Performance_Dashboard.pbix

├── images/
│   ├── executive_overview.png
│   ├── product_customer_analysis.png
│   └── profitability_analysis.png

└── README.md


## Dataset

Dataset used for this project was obtained from a publicly available retail sales dataset.

The dataset is used for educational and portfolio purposes.
All dataset rights belong to the original provider.
