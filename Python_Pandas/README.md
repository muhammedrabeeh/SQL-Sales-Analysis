Pandas was used in this project to prepare raw retail data for analysis and visualization.
The focus was on data cleaning, validation, and analytical data modeling, ensuring the dataset is accurate, consistent, and ready for downstream tools like Power BI.
Pandas was not used for final reporting, but as a data preparation layer between raw data and business analysis.

-Input Data
The following raw datasets were used:
Customer – customer details and demographics
Product – product hierarchy and attributes
Sales – transactional sales data (sales, quantity, discount, profit)
These datasets were loaded separately and treated as source tables.

-Data Cleaning Steps
The following cleaning steps were applied using Pandas:
Standardized column names (lowercase, underscores instead of spaces)
Checked and handled missing values in critical columns
Removed duplicate records based on business-relevant keys
validated numeric ranges (e.g., discount, quantity, profit)
Ensured data types were appropriate (numeric and datetime fields)
Cleaning rules were applied conservatively to preserve real business behavior while removing invalid or corrupt records.

-Data Modeling
An analytical data model (star-schema style) was created using Pandas:
Sales table used as the fact table
Customer and Product tables used as dimension tables
Tables were merged using appropriate keys with left joins to preserve transactional integrity
This structure supports efficient analysis and BI reporting.

-Data Validation
After cleaning and modeling, validation checks were performed to ensure data reliability:
Row count comparison before and after cleaning
Verification of total sales and profit consistency
Sanity checks on key metrics to confirm logical behavior
These steps ensured the final dataset was trustworthy for business analysis.

Output
The final cleaned and modeled dataset was exported as a CSV file:

cleaned_store_data.csv

This file serves as the single source of truth for analysis and was used as the input for Power BI dashboards and further analysis.
