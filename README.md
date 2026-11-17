# Sales Data Analysis using Python

## Project Overview

This project explores a sales dataset to understand business performance, identify revenue patterns, and generate data-driven recommendations.

Using Python, Pandas, NumPy, Matplotlib, and Seaborn, I performed data cleaning, exploratory data analysis (EDA), and business-focused analysis to investigate product performance, revenue trends, customer contribution, country-wise sales, order statuses, and discounting patterns.

The project answers seven business questions and concludes with recommendations based on the findings.

## Dataset Information

- **Dataset:** Sales Data Sample
- **Rows:** 2,823
- **Original columns:** 25
- **Date range:** January 6, 2003 – May 31, 2005
- **Format:** CSV

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Project Workflow

1. Data loading and initial inspection
2. Data cleaning and transformation (ETL)
3. Missing-value analysis and treatment
4. Data type conversion
5. Duplicate checking
6. Data validation
7. Exploratory data analysis
8. Business question analysis
9. Insights and recommendations

## Business Questions

### 1. Product-Line Performance

- Which product lines generate the highest sales revenue?
- Do the highest-revenue product lines also have the highest order quantities?
- Which product lines may deserve more marketing attention?

### 2. Revenue Trends and Seasonality

- How does revenue change over time?
- What are the monthly and yearly revenue patterns?
- Does the dataset provide complete year coverage for a fair comparison?

### 3. Customer Revenue Contribution

- Who are the top 10 customers by revenue?
- What percentage of total revenue comes from these customers?
- How much revenue is contributed by the top 3 customers?

### 4. Country and Territory Performance

- Which countries and territories generate the highest revenue?
- Which markets receive the most orders?
- How does average revenue per order differ across countries?

### 5. Order Status Analysis

- How much order value is associated with Cancelled, Disputed, and On Hold orders?
- Which product lines are most affected?
- Which product lines may need further investigation?

### 6. MSRP and Discount Analysis

- How often are products sold below MSRP?
- How large are the price differences?
- Which product lines have the most below-MSRP sales?
- How do discounts relate to deal size and quantity ordered?

### 7. Business Recommendations

Based on the analysis, identify three practical actions that could help improve sales performance and reduce potential revenue risks.

## Key Findings

- Classic Cars generated the highest recorded sales revenue among the product lines.
- The top 10 customers contributed approximately 29.45% of total revenue.
- The top 3 customers contributed approximately 17.62% of total revenue.
- The United States generated the highest country-level revenue.
- Orders with Cancelled, Disputed, and On Hold statuses represented approximately $445,679 in associated sales value.
- A substantial number of records had a selling price below MSRP.
- The analysis also explored differences in revenue per order across countries and discount patterns across deal sizes.

## Important Note

Sales revenue is not the same as profit. This project analyzes the recorded sales amounts and does not calculate actual profit because product cost data was not established in the analysis.

Order values associated with Cancelled, Disputed, and On Hold statuses should also be treated as potentially affected order value, not automatically as realized revenue or confirmed losses.

## Project Structure

```text
sales-data-analysis-python/
│
├── README.md
├── Sales_Data_Analysis.ipynb
├── cleaned_data.csv
└── .gitignore
```

The cleaned dataset may be included only if its source and license permit redistribution.

## Learning Outcomes

Through this project, I practiced:

- Cleaning and transforming real-world sales data
- Handling missing values and inconsistent records
- Working with dates and time-based analysis
- Grouping and aggregating data using Pandas
- Comparing product, customer, and country performance
- Analyzing price differences and discounts
- Translating data findings into business recommendations

## Conclusion

This project demonstrates how Python-based data analysis can turn raw sales records into useful business insights. It helped me practice the complete workflow, from data preparation and validation to exploratory analysis and recommendation development.
