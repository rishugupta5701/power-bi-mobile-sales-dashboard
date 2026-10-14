# 📱 Mobile Sales Analysis Dashboard | Power BI

<p align="center">
  <strong>An Interactive Business Intelligence Dashboard for Mobile Sales Performance Analysis</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Business-Intelligence-blue?style=for-the-badge" alt="Business Intelligence"/>
  <img src="https://img.shields.io/badge/Project-Data%20Analytics-2E8B57?style=for-the-badge" alt="Data Analytics"/>
</p>

<p align="center">
  <a href="https://github.com/rishugupta5701">GitHub Profile</a> •
  <a href="https://www.linkedin.com/in/rishu-gupta-717915335/">LinkedIn Profile</a>
</p>

---

## 📌 Project Overview

The **Mobile Sales Analysis Dashboard** is an interactive Power BI project developed to analyze mobile phone sales performance across multiple business dimensions.

The dashboard presents key performance indicators (KPIs), sales trends, geographic performance, customer ratings, payment preferences, and mobile model comparisons in an organized and interactive format.

The primary objective is to transform sales data into meaningful business information that helps users understand performance, identify patterns, compare product categories, and explore sales trends.

This project demonstrates practical applications of data visualization, business intelligence, KPI reporting, and interactive dashboard development using Microsoft Power BI.

---

## 🎯 Business Objectives

The main objectives of this project are to:

- Monitor overall mobile sales performance using KPIs.
- Analyze sales and quantity trends over time.
- Understand geographic variations in sales performance.
- Compare the performance of different mobile brands and models.
- Examine customer ratings and payment preferences.
- Identify patterns that may support business planning and decision-making.
- Present complex sales information through interactive visualizations.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and data visualization |
| Power Query | Data preparation and transformation, where applicable |
| DAX | KPI calculations and analytical measures, where applicable |
| Data Modeling | Organizing data and relationships, where applicable |
| Interactive Visualizations | Exploring trends, comparisons, and business performance |

---

## 📊 Dashboard Features

### 1. Key Performance Indicators (KPIs)

The dashboard includes high-level sales performance indicators that provide a consolidated overview of the business.

These KPIs help users understand overall performance before exploring individual dimensions.

### 2. Sales Trend Analysis

The dashboard enables users to explore sales activity over time.

**Business value:**
- Understand changes in sales performance.
- Identify periods of higher or lower activity.
- Compare performance across available time periods.

### 3. City-Wise Sales Analysis

Geographic visualizations help explore differences in mobile sales across cities.

**Business value:**
- Compare sales contributions by location.
- Identify geographic variations in performance.
- Support further investigation of regional sales opportunities.

### 4. Brand-Wise Sales Analysis

The brand comparison visual helps users compare the brands displayed in the dashboard.

**Important note about the brand filter:**

The brand table currently displays only four brands because of its filter configuration. The overall sales KPI, however, includes sales from all brands in the underlying data.

Consequently, the sum of the brands visible in the table may differ from the overall sales KPI.

**This difference is expected under the current visual-filter configuration. It does not, by itself, indicate an error in the overall sales calculation.**

The brand table should therefore be interpreted as a filtered comparison rather than a complete reconciliation of total sales.

### 5. Mobile Model Analysis

The dashboard supports comparisons between mobile models using the available sales metrics.

**Business value:**
- Compare model-level performance.
- Explore differences between products.
- Identify models that may warrant further investigation.

### 6. Customer Ratings Analysis

Customer rating visualizations provide a way to examine the distribution of ratings in the available dataset.

**Business value:**
- Understand customer feedback patterns.
- Compare rating distributions.
- Investigate potential relationships between customer ratings and product performance.

The dashboard presents rating patterns; it does not establish that ratings cause changes in sales.

### 7. Payment Method Analysis

The payment analysis visual explores the distribution of transactions across the payment methods recorded in the dataset.

**Business value:**
- Understand payment preferences.
- Compare transaction distributions.
- Support further investigation of payment behavior.

### 8. Interactive Filtering

Interactive filters allow users to explore subsets of the data and examine how displayed metrics change with the selected context.

This makes the dashboard useful for both high-level reporting and more focused analysis.

---

## ❓ Business Questions Addressed

The dashboard is designed to help investigate the following questions.

### Sales Performance
1. What is the overall sales performance?
2. How does sales quantity vary over time?
3. Which periods show relatively higher or lower sales activity?
4. How does performance change when different filters are applied?

### Geographic Analysis
5. How do mobile sales vary across cities?
6. Which cities contribute to the sales represented in the dashboard?
7. What geographic differences warrant further investigation?

### Product & Brand Analysis
8. How do the displayed mobile brands compare?
9. Which mobile models show stronger performance under the selected metrics?
10. How does product performance vary across the available categories?
11. How do brand comparisons change when visual filters are applied?

### Customer Analysis
12. How are customer ratings distributed?
13. What patterns appear in the recorded customer ratings?
14. Which rating categories may warrant further investigation?

### Payment Analysis
15. How are transactions distributed across payment methods?
16. Which payment methods account for the largest share of the displayed transactions?

### Data Interpretation
17. Why might the sum of visible brand values differ from the overall sales KPI?
18. How do filters affect the interpretation of dashboard metrics?
19. Which findings require additional analysis before business recommendations can be made?

*These questions describe the analytical scope of the dashboard. Specific findings should be established by examining the actual data and visual results.*

---

## 💡 Business Insights & Interpretation

The dashboard provides a framework for investigating business performance through several analytical dimensions.

The following areas describe the types of insights that can be investigated using the report.

| Analytical Area | Insight to Investigate | Potential Business Application |
|---|---|---|
| Sales Trends | Periods with relatively high or low sales activity | Sales planning and performance monitoring |
| Geographic Performance | Differences in sales across cities | Regional performance evaluation |
| Brand Comparison | Differences among the brands displayed | Product portfolio analysis |
| Model Performance | Differences among mobile models | Product performance evaluation |
| Customer Ratings | Distribution and variation in customer ratings | Customer experience investigation |
| Payment Methods | Distribution of transactions by payment method | Payment behavior analysis |
| Filter Behavior | Differences between overall KPIs and filtered visuals | Accurate interpretation of reports |

### Important Analytical Observation: Brand Filter vs. Total Sales KPI

The dashboard uses different filter contexts for the overall sales KPI and the brand comparison visual.

- **Overall sales KPI:** Includes sales across all brands.
- **Brand comparison table:** Displays only four brands under its current filter configuration.
- **Result:** The sum of the displayed brand values may not equal the overall sales KPI.

This distinction is important when interpreting the report.

The KPI represents the overall sales total, while the brand table provides a filtered view of brand-level performance.

The appropriate comparison depends on the analytical question being asked. If a complete reconciliation of sales by brand is required, the visual filters and included brands must be considered.

### From Observations to Business Decisions

A useful analytical workflow separates three elements:

1. **Observation:** What the dashboard actually shows.
2. **Interpretation:** What the observed pattern may indicate.
3. **Recommendation:** What action could reasonably follow from the finding.

For example, a difference in sales across cities is an observation. Investigating possible differences in demand, customer behavior, or product availability is an analytical next step. Any recommendation should be supported by additional evidence where necessary.

This approach helps avoid unsupported conclusions and keeps business recommendations grounded in the available data.

---

## 🔄 Analytical Workflow

The project follows a business-oriented analytical workflow.

### Step 1: Understand the Business Problem
Identify the sales performance questions the dashboard should help answer.

### Step 2: Prepare the Data
Inspect the dataset and perform the necessary preparation and transformation steps.

### Step 3: Develop the Analytical Measures
Create or configure the measures needed to represent the relevant sales KPIs.

### Step 4: Build the Dashboard
Organize the visualizations to present overall performance, trends, geographic comparisons, and customer-related metrics.

### Step 5: Enable Interactive Exploration
Configure the relevant filters and interactions to support focused analysis.

### Step 6: Validate the Results
Review KPI calculations, visual filters, and the interpretation of displayed values.

### Step 7: Communicate Findings
Use the dashboard to investigate business questions and develop evidence-based insights.

*This workflow describes the project approach. The exact implementation details depend on the measures, transformations, and model used in the Power BI file.*

---

## 📈 Skills Demonstrated

This project demonstrates practical work in the following areas:

- Business Intelligence and reporting.
- Interactive dashboard development.
- Sales KPI visualization.
- Time-based performance analysis.
- Geographic data visualization.
- Product and brand comparisons.
- Customer rating analysis.
- Payment method analysis.
- Filter-context interpretation.
- Communicating analytical findings.

The project also highlights the importance of understanding how filters influence visualizations and how that affects business interpretation.

---

## ⚠️ Data Interpretation & Limitations

When interpreting this dashboard, consider the following points:

1. **Brand filter:** The brand comparison table displays four brands, while the overall sales KPI includes all brands.
2. **Visual context:** A filtered visualization may represent only a subset of the underlying data.
3. **Metric definitions:** Sales, quantity, and other measures should be interpreted according to their definitions in the report.
4. **Data coverage:** Findings are limited to the information available in the underlying dataset.
5. **Causation:** Observed patterns do not establish causal relationships without additional analysis.
6. **Business recommendations:** Recommendations should be based on verified findings rather than assumptions.

These considerations support transparent and accurate reporting.

---

## 🚀 How to Explore the Project

1. Open the project repository.
2. Review the dashboard screenshots, if available.
3. Download the `.pbix` file if it has been included and is accessible to you.
4. Open the file using Microsoft Power BI Desktop.
5. Explore the report pages and available interactive filters.
6. Compare the KPI values with the relevant visualizations.
7. Review the brand filter configuration when interpreting brand-level sales.

**Note:** Opening the report locally requires compatible Power BI Desktop software. Any external data connections or additional dependencies may also need to be configured.

---

## 👨‍💻 About the Author

**Rishu Gupta**

Aspiring Data Analyst interested in Data Analytics, Business Intelligence, and data-driven decision-making.

I am building practical projects to strengthen my analytical skills and communicate business findings through meaningful visualizations.

### Connect With Me

- **GitHub:** [rishugupta5701](https://github.com/rishugupta5701)
- **LinkedIn:** [Rishu Gupta](https://www.linkedin.com/in/rishu-gupta-717915335/)

---

## ⭐ Final Note

This project reflects my interest in transforming sales data into meaningful visual reports and exploring how business intelligence can support better decision-making.

I welcome constructive feedback and suggestions that can help improve the analytical quality, usability, and presentation of this dashboard.

<p align="center">
  <strong>Thank you for visiting my project!</strong>
</p>
