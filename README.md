# Mobile Sales Analysis Dashboard | Power BI

> An interactive Power BI project exploring mobile-phone sales, transactions, product performance, customer ratings, and payment preferences.

**Author:** Rishu  
**Project type:** Power BI / Business Intelligence portfolio project  
**Learning acknowledgment:** Created as part of my learning journey with skill course, with guidance from Satish dhawale Sir.

---

## Project Overview

This project presents a **Mobile Sales Dashboard** built in Microsoft Power BI. It brings key sales metrics and several views of the business into one report, helping users explore performance by month, city, mobile model, brand, customer rating, and payment method.

The goal is to practise transforming sales data into a clear visual report and to demonstrate how a dashboard can support business questions and further investigation.

> **Learning-project note:** This project was created as part of a guided learning experience. The dashboard and documentation are intended to demonstrate my learning and analytical approach. Any findings below should be treated as observations from the displayed report and validated against the underlying data before being used for business decisions.

## Dashboard Preview

![Mobile Sales Dashboard](screenshots/mobile_sales_dashboard.png)

*Add a screenshot of your dashboard to the `screenshots` folder using the filename `mobile_sales_dashboard.png`. If you use a different filename, update the image path above.*

## Dashboard Features

The report currently includes the following visuals and metrics:

- **Total Sales** — headline sales KPI.
- **Transactions** — transaction-count KPI.
- **Average Order Value** — average-order-value KPI.
- **Total Quantity** — quantity KPI.
- **City-wise Sales** — map showing sales by city.
- **Monthly Quantity Trend** — line chart comparing quantity across the months.
- **Customer Ratings** — distribution of customer ratings.
- **Transactions by Payment Method** — share of transactions across UPI, debit card, credit card, and cash.
- **Sales by Mobile Model** — comparison of selected mobile models.
- **Sales by Day Name** — daily sales comparison.
- **Brand Performance Table** — brand-level sales and transaction comparison.

### Interactive Filters

The dashboard includes filters for:

- Mobile model
- Payment method
- Brand
- Month
- Same period last year (where configured in the report)

The available filters and their exact behavior depend on the Power BI report configuration.

## Tools and Skills

The dashboard is built in **Microsoft Power BI**. The project demonstrates dashboard design and sales analysis through interactive visuals.

Add or retain the following technologies only if you used them in your own report:

- Microsoft Power BI
- Power Query — data transformation and cleaning
- DAX — calculated measures and KPIs
- Data modeling — tables and relationships
- Data visualization
- Business analysis

## Business Objectives

The dashboard is intended to help explore questions such as:

1. What are the overall sales, transaction count, average order value, and quantity sold?
2. How does quantity sold change from month to month?
3. Which cities show higher or lower sales in the report?
4. Which mobile models have the strongest sales performance?
5. How do sales compare across brands?
6. Which payment methods account for the largest share of transactions?
7. How are customer ratings distributed?
8. Does sales performance vary by day of the week?
9. How do the results change when filtering by brand, mobile model, payment method, or month?
10. Where should the business investigate further to understand sales or customer behavior?

## Preliminary Business Insights

The following are **observations from the dashboard screenshot**, not independently audited results. Verify them against the underlying data and measure definitions before presenting them as final findings.

### 1. Brand performance

The visible brand table shows Apple with the highest displayed sales among the listed brands:

- Apple: ₹16,16,15,730
- Samsung: ₹16,00,38,055
- OnePlus: ₹15,37,19,439
- Vivo: ₹15,00,78,428

**Possible follow-up:** Compare profit and profit margin, if cost data is available, before concluding which brand is most valuable to the business.

### 2. Monthly quantity trend

The visible monthly quantity chart shows:

- **Highest displayed month:** July — 1,700 units
- **Lowest displayed month:** February — 1,451 units

**Possible follow-up:** Investigate whether the pattern is associated with promotions, stock availability, seasonal demand, or other factors. The chart alone does not establish the cause.

### 3. Payment-method preference

The visible payment chart shows the following approximate shares of transactions:

- UPI: 26.36%
- Debit Card: 24.72%
- Credit Card: 24.69%
- Cash: 24.22%

UPI has the largest displayed share in this chart.

**Possible follow-up:** Compare payment preferences across cities or brands to see whether patterns differ by segment.

### 4. KPI reconciliation to complete

The screenshot displays headline Total Sales of approximately **₹769M**, while the brand table's visible total is approximately **₹625.45M**. These figures do not appear to match.

Before publishing final conclusions, investigate whether this is caused by filters, different measure definitions, incomplete brand coverage, or another report/model issue. Do not assume either figure is correct until the measures and filter context have been checked.

## Business Questions for Further Analysis

These questions can guide future improvements to the report:

### Sales performance
- What are total sales and total profit for the selected period?
- What is the sales growth rate compared with the previous period or year?
- Which months have the highest and lowest sales?
- Does quantity sold move in the same direction as sales revenue?

### Product and brand performance
- Which brands generate the most revenue?
- Which mobile models sell the most units?
- Which products generate the highest profit, if cost data is available?
- Are there high-revenue products with comparatively low profit margins?

### Geographic performance
- Which cities contribute most to total sales?
- Which cities have lower sales and may need further investigation?
- Do brand or model preferences vary by city?

### Customer and payment behavior
- Which payment methods are used most frequently?
- Does payment-method preference vary by city or brand?
- What is the distribution of customer ratings?
- Do ratings vary by mobile model or brand, if the data supports this comparison?

### Time-based analysis
- How does performance vary by month?
- Are there recurring seasonal patterns across multiple years?
- Which days of the week have higher sales?
- How does the selected period compare with the same period last year?

## Potential Business Recommendations

Recommendations should be based on validated results, not assumptions. Possible areas to investigate include:

- Review stock planning for months with higher observed demand.
- Investigate possible causes of lower-quantity months.
- Compare brand revenue with profit and margin before making inventory decisions.
- Examine customer ratings to identify products or service areas that may need attention.
- Review payment preferences by customer segment or location.
- Compare current results with previous periods to distinguish one-time changes from recurring trends.

These are suggested lines of investigation, not claims that any particular action will improve performance.

## Data Preparation and Modeling

Document the actual steps performed in your Power BI workflow. For example, if applicable:

- Handling missing or duplicate records
- Correcting data types and formatting
- Transforming columns in Power Query
- Creating or checking relationships between tables
- Creating a date table or month sorting logic
- Defining DAX measures for sales, transactions, quantity, and average order value

**Only include steps you actually completed.** If you are unsure whether a transformation or measure is correct, validate it in Power BI before documenting it.

## DAX Measures

Add the key measures from your report here, with a short explanation of what each calculates.

Examples of measures to document, if present in the model:

- Total Sales
- Total Transactions
- Average Order Value
- Total Quantity
- Sales for the same period last year
- Sales or quantity by selected period

For each measure, explain the definition and denominator where relevant. In particular, confirm whether “Transactions” means transaction rows, transaction IDs, or distinct orders, and make sure Average Order Value uses the intended order count.

## How to View the Project

1. Open the `.pbix` file in a compatible version of Microsoft Power BI Desktop.
2. Review the main dashboard page.
3. Use the slicers and filters to explore the data.
4. Review the business questions and preliminary insights in this README.

If you publish an interactive online version, make sure you have permission to share the entire dataset and report model publicly. Do not use public publishing for confidential or sensitive data.

## Project Limitations and Next Steps

Planned improvements may include:

- Reconciling headline sales with the brand-table total.
- Validating KPI and DAX definitions.
- Adding verified findings and concise recommendations.
- Comparing sales and profit, if cost data is available.
- Improving year-over-year analysis, if multiple years of data are available.
- Documenting data sources, transformations, and model relationships.

## Acknowledgment

I am grateful to **SkillCourse and Satish Dwhale Sir** for their guidance during my Power BI learning journey. This project helped me practise dashboard creation and explore how data visualization can support business analysis.

## Author

**Rishu**  
Aspiring Data Analyst | Power BI | Data Visualization | Business Analysis

- **GitHub:** Add your GitHub profile URL
- **LinkedIn:** Add your LinkedIn profile URL

---

*This README should be updated as the report is validated and improved. Confirm all metrics and insights against the underlying Power BI model before using them in business decisions or interviews.*
