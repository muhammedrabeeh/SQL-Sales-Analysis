Storedata Sales Performance Analysis

-Project Overview:
This project analyzes sales and profitability performance of a retail superstore using historical order data from 2014 to 2017.
The objective is to understand business growth trends, identify top-performing and underperforming regions and products, and uncover profitability risks that can support better decision-making.

The analysis was performed using SQL for data analysis, Excel,power query for initial data cleaning and  validation, and Power BI, DAX for interactive visualization and business storytelling.

-Business Questions:
How have sales and profit evolved over time?
Which regions and product categories drive the most revenue?
Which products contribute most to profit, and which generate losses?
Are there seasonal patterns in sales performance?
Does higher discounting improve profitability?

-Data Source
Dataset: Stordata Dataset
Format: Excel
Key Tables: customer , product, sales 

- Data Preparation (Excel):
Reviewed the dataset for missing and duplicate values
Validated date formats and numeric fields (sales, profit, discount)
Performed an initial understanding of key dimensions such as region, category, and sub-category
Ensured the data was ready for SQL-based analysis

-SQL Analysis (PostgreSQL):
SQL was used to perform structured analysis and generate insights, including:
Aggregation of total sales and profit by year
Regional performance analysis
Category and sub-category profitability analysis
Identification of loss-making products
Monthly sales trend and seasonality analysis
Use of joins, aggregations, window functions, and views to support analysis and reporting
The SQL queries are organized and documented in the sql/ folder.

-Power BI Dashboard:
An interactive Power BI dashboard was built to visualize key findings and support business interpretation.
DAX used to find the profit margin

-The dashboard includes:
KPI cards for Total Sales, Total Profit, and Profit Margin
Year-over-year sales and profit trends (2014–2017)
Regional and category-wise performance comparisons
Product-level profitability analysis
Monthly sales trends highlighting seasonality
Filters for region and category to enable dynamic analysis

-Key Insights:
Sales and profit increased consistently from 2014 to 2017, indicating steady business growth
Total sales grew from $3.37M to $5.86M, while profit increased from $434K to $721K
The West region is the highest revenue-generating region, while the South underperforms
Technology is the top-performing category by sales
Canon Image Class is the most profitable and highest-selling product
Tables and Bookcases are consistently loss-making despite generating sales
Sales peak during November and December, while February and March show lower demand
Higher discounts do not consistently lead to higher profitability

- Conclusion
This project highlights a business with strong overall growth, but also reveals profitability risks at the product and regional level.
By focusing on high-margin products, improving underperforming regions, and optimizing discount strategies, the company can further improve profitability and reduce risk.
