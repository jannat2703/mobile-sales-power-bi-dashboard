# Mobile Sales Performance Dashboard

## Project Overview
An interactive two-page Power BI report analyzing mobile sales performance by brand, city, mobile model, payment method, customer age group, customer rating, and time.

## Dashboard Preview

### Executive Overview
![Executive Overview](images/executive-overview.png)

### Detailed Analysis
![Detailed Analysis](images/detailed-analysis.png)

## Business Questions
- Which mobile brand sells the most units?
- Which city leads mobile sales?
- In which month does revenue peak?
- Which model generates the most revenue?
- Which payment method is used most?
- Which customer age group generates the most revenue?
- Which brands receive stronger customer ratings?

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Excel/CSV dataset

## Data Preparation
- Standardized inconsistent weekday names.
- Created `Weekday Sort` for Monday-to-Sunday ordering.
- Created `Age Group` and `Age Group Sort` for demographic analysis.
- Checked data types and cleaned text inconsistencies.
- Created DAX measures for revenue, units sold, transactions, customer ratings, transaction value, and selling price.

## Key KPIs
- Total Units Sold
- Total Revenue
- Total Transactions
- Average Customer Rating
- Average Transaction Value
- Average Selling Price

## Key Insights

### Executive Overview
- Apple leads sales with 3,932 units sold.
- Delhi is the leading city with 5,078 units sold.
- Revenue peaks in July at ₹69.64M.
- Xiaomi has the highest average customer rating at 3.72/5.

### Detailed Analysis
- iPhone SE generates the highest model revenue at ₹59.57M.
- UPI is the most-used payment method with 552 transactions.
- Customers aged 25–34 generate the highest revenue at ₹84.46M.

## Dashboard Pages
1. **Executive Overview** — sales KPIs, brand/city comparison, monthly revenue trend, customer ratings, and executive insights.
2. **Detailed Analysis** — model revenue, payment-method usage, age-group revenue, and brand/model summary.

## Limitations
The dataset does not include product cost, discount, inventory, profit, or sales-target information. This dashboard evaluates sales volume, revenue, transaction activity, and customer ratings; it does not evaluate profitability or target attainment.
