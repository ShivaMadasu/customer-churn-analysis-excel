# Customer Churn Analysis (Excel) – Databel Telecom Case Study

An Excel analysis of customer churn for **Databel**, a fictional telecom company, completed as a DataCamp case study. The goal was to find who is churning, why, and where retention effort should go.

## Business Question
Why are customers leaving Databel, and which customer segments are most at risk?

## Dataset
- **Customers sheet:** 6,687 customers (one row per customer) with churn label, plan, contract, payment method, usage, demographics, churn category and reason.
- **Aggregate sheet:** the same data summarised by segment, with `Total Customers` and `Churned Customers` columns.
- Source: DataCamp case-study data (fictional company).

## Tools & Skills
Excel · PivotTables · Calculated Fields · Nested IF · Charts · Data preparation · Segmentation

## What I Did
1. Prepared the data: renamed fields to readable headers and created a **Demographics** column (Under 30 / Senior / Other) with a nested `IF()`.
2. Built PivotTables showing total customers, churned customers and a reusable **Churn Rate %** calculated field.
3. Ranked churn reasons and showed each as a % of all churned customers.
4. Analysed churn by age group, demographics, state and international plan, and by tenure and contract type.
5. Grouped monthly data usage (under 5 GB, 5–10 GB, 10+ GB) to test whether unlimited-plan churn is linked to consumption.
6. Added charts to present the findings.

## Key Findings
- Overall churn rate is **26.86%** (1,796 of 6,687 customers).
- **Competitors** drive the largest share of churn: about **45%** of churned customers left for a competitor. "Competitor made better offer" is the single top reason (**16.9%**).
- **Seniors** churn at **38.2%**, against 23.0% for under-30s.
- Customers on an **unlimited data plan** churn at about **32%**, double the roughly 16% of other customers. The highest churn is among unlimited customers who use under 5 GB a month.
- Churn varies widely by state, but several state and plan combinations have very small samples, so those rates should be read with caution.

## Recommendations
- Launch competitor-match offers and device upgrade deals for at-risk customers.
- Review unlimited-plan pricing for low-usage customers.
- Create a retention programme aimed at senior customers.

## Files
- `Churn_Analysis_Project.xlsx` – full workbook with data, PivotTables and charts
- `README.md` – this summary
