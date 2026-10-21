# Proffesional Sales Data Analysis with Python and Pandas

## Project Overview

This project analyzes sales transaction data to help business understand its sales performance ,profitablity, and product trends.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Visual Studio Code

## Data Cleaning and Preparation

The raw dataset was inspected for missing values,duplicate records,inconsistent text formatting, and date-format issues.

The following steps were performed:

- Remove duplicate records.
- Standardized region and product category names.
- Converted order dates to datetime format.
- Filled one missing unit price using the known price of the same product.
- Created a profit column by subtracting cost from sales.
- Saved the cleaned dataset for further analysis.

## Analysis Performed

The analysis explored sales performance from different business perspectives:

- Total sales by region.
- Total sales by product.
- Monthly sales trends.
- Total profit by product.
- Overall sales,costs,and profit margin.

## Key Findings

- The south region the highest total sales.
- Laptops generated the highest total profit among the product analyzed.
- Pens generated the lowest total profit.
- January recorded the highest monthly sales.
- September recorded the lowest monthly sales.
- The profit margin for orders with known costs was approximately 29.99%.

## Data Quality Limitaion

Some missing values remain in the cleaned dataset:

- Three missing Region values.
- Two missing Segment values.
- Two missing Product Category values.
- One missing Cost value ,which also result in a missing Profit value.

These values were not guessesd or filled with unsupported information .The affected records should be reviewed with the client before further decisions are made.

## Project Files

- data/sales_data_raw.csv -Original dataset.
- data/sales_data_cleaned.csv -Cleaned dataset.
- data/sales_summary.csv -Summary of key business metrics.
- notebooks/sales_analysis.ipynb -Notebook containing the analysis and visualization.

## Conclusion

This project demonstrate practical skills in data cleaning,exploratory data analysis, business metric calculation, and data visualization using Python and Pandas.

The findings can help a business understand its sales perfomance, identify profitable products, and investigate monthly sales trends.
