# Retail Sales & Profitability Analysis

## Project Overview

This project analyzes retail sales transactions to identify the key drivers of profitability across products, customer segments, geographic regions, and discount levels. Using Python and pandas, I explored over 9,900 transactions to uncover patterns in sales performance and generate business recommendations.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

- Sample Superstore Dataset
- 9,994 transactions
- 21 variables including sales, profit, discount, category, customer segment, and region

## Business Questions

1. Which product categories generate the most sales and profit?
2. Which regions perform best?
3. Which customer segments contribute the most revenue and profit?
4. How do discounts affect profitability?
5. Which products generate losses despite strong sales performance?

## Key Findings

### Technology Leads Profitability

Technology generated the highest sales and profit among all product categories, outperforming Furniture and Office Supplies.

### West Region Outperformed Other Markets

The West region generated the highest overall sales and profits, making it the strongest geographic market.

### Consumer Segment Drives Revenue

Consumer customers generated the largest share of sales and profit across all customer segments.

### Excessive Discounts Reduce Profitability

Orders receiving discounts greater than 30% were associated with negative average profits.

### Tables Generated High Sales but Significant Losses

Tables produced over $206,000 in sales but approximately $17,700 in losses. Additional analysis revealed a strong negative correlation (-0.67) between discounts and profitability for Table sales.

## Business Recommendations

- Reevaluate discounting strategies for Tables.
- Expand investment in high-performing Technology products.
- Investigate margin issues within Furniture sub-categories.

## Visualizations

- Profit by Product Sub-Category
- Sales vs Profit by Category
- Profit by Region
- Average Table Profit by Discount Level

## Project Structure

```text
retail-sales-analysis/
│
├── README.md
├── retail_sales_analysis.ipynb
├── visuals/
│   ├── profit_by_subcategory.png
│   ├── sales_vs_profit_category.png
│   ├── profit_by_region.png
│   └── table_discount_profit.png
```

## Author

Noah Vongsengdeuane
Economics Student | Aspiring Data Analyst
