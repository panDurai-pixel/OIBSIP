# Exploratory Data Analysis on Retail Sales Data

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Global Superstore dataset to understand sales performance, profitability, customer behavior, product performance, geographical trends, discounts, and shipping operations.

The objective is to transform raw retail transaction data into meaningful business insights that support data-driven decision-making.

## Dataset

The dataset contains 51,290 retail transaction records with information including:

- Order and shipping dates
- Shipping mode and order priority
- Customer segment
- Market and region
- Product category and sub-category
- Sales and quantity
- Discount and profit
- Shipping cost

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preparation

The following data preparation steps were performed:

- Inspected the dataset structure and data types
- Checked for missing values
- Converted order and shipping dates to datetime format
- Cleaned the sales column by removing commas
- Converted sales values from text to numeric format
- Generated descriptive statistics for numerical variables

## Exploratory Data Analysis

The analysis covered:

- Overall business performance using key performance indicators
- Yearly sales trends
- Monthly sales trends
- Quarterly sales trends
- Sales by category and sub-category
- Profit by category and sub-category
- Sales and profit by market
- Sales and profit by region
- Customer segment performance
- Relationship between discount and profit
- Top products by sales
- Top products by profit
- Shipping mode analysis
- Correlation analysis
- Order priority analysis

## Key Insights

- 2014 recorded the highest sales at approximately $4.30 million.
- Technology was the highest-selling category at approximately $4.74 million.
- Technology was also the most profitable category, generating approximately $663.78 thousand in profit.
- Tables was the only loss-making sub-category, with a loss of approximately $64.08 thousand.
- APAC was the highest-performing market by sales at approximately $3.59 million.
- Central was the highest-performing region by sales at approximately $2.82 million.
- The Consumer segment generated the highest sales at approximately $6.51 million.
- Discount and profit had a moderate negative correlation of -0.316.
- Sales and shipping cost had a strong positive correlation of 0.768.
- Standard Class was the most frequently used shipping mode.
- Medium was the most common order priority.

## Business Recommendations

- Continue investing in the Technology category because it leads in both sales and profit.
- Investigate the pricing, discount levels, costs, and shipping expenses of the loss-making Tables sub-category.
- Apply discounts strategically because higher discounts tend to be associated with lower profitability.
- Strengthen operations and marketing in the APAC market and Central region.
- Continue focusing on the Consumer segment while exploring growth opportunities in other customer segments.
- Monitor and optimize shipping expenses for high-value orders.

## Conclusion

The analysis identified important trends in sales growth, profitability, customer segments, product performance, geographical performance, discounts, and shipping operations.

The findings demonstrate how exploratory data analysis can transform raw retail transaction data into actionable business insights and support better data-driven decision-making.

## Repository Structure

```text
DataAnalytics-L1-EDARetailSales/
├── dataset.csv
├── retail_sales_eda.ipynb
└── README.md