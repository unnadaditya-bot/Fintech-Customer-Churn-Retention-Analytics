# Fintech Customer Churn & Retention Analytics

Tools: MySQL · Microsoft Excel
Domain: Fintech · Customer Analytics · Customer Retention

---

# Business Problem

Customer attrition is one of the most important challenges for financial institutions. Losing existing customers not only reduces revenue but also increases customer acquisition costs.

This project analyzes customer churn behavior for a fintech credit card business to identify:

* Which customer segments are most likely to churn
* Which behavioral factors drive attrition
* How much revenue is at risk
* What actions the retention team should prioritize

---

# Project Objective

The objective of this project was to use SQL and Excel to transform raw customer data into actionable business insights that can support customer retention decisions.

Key business questions:

* Which card categories experience the highest churn?
* Does customer inactivity increase churn risk?
* Which income segments contribute the most revenue at risk?
* Can transaction behavior act as an early churn warning signal?
* Which customers should be targeted for retention campaigns?

---

# Dataset

**Source:** Credit Card Customer Churn Dataset (Kaggle)

Dataset contains customer-level information including:

* Customer demographics
* Income category
* Card category
* Credit limit
* Transaction amount
* Transaction count
* Inactivity behavior
* Customer attrition status

Additional fields created during preparation:

* Churn_Flag
* Age_Group
* Tenure_Group

---

# Tools Used

| Tool            | Purpose                                 |
| --------------- | --------------------------------------- |
| MySQL Workbench | Data cleaning and business analysis     |
| Microsoft Excel | Dashboard development and visualization |

---

## Project Workflow

# 1. Data Preparation

* Removed unnecessary columns
* Created churn indicator field
* Created customer segmentation fields
* Structured dataset for SQL analysis

# 2. SQL Analysis

Performed multiple business-focused analyses including:

* Overall churn analysis
* Card category churn analysis
* Inactivity impact analysis
* Income segment analysis
* Customer tenure analysis
* Transaction behavior analysis
* High-value customer loss analysis

# 3. Dashboard Development

Created an executive Excel dashboard featuring:

* KPI cards
* Business charts
* Customer churn insights
* Retention recommendations

---

## Key Metrics

| Metric                    | Value      |
| ------------------------- | ---------- |
| Total Customers           | 2,037      |
| Churned Customers         | 339        |
| Churn Rate                | 16.64%     |
| Revenue at Risk           | $1,850,504 |
| Average Transaction Value | $6,443     |

---

## Key Findings

# 1. Transaction Activity is the Strongest Churn Signal

Customers with very low transaction frequency showed significantly higher churn rates than highly engaged customers.

Low customer activity can serve as an early warning signal for retention teams.

---

# 2. Customer Inactivity Drives Attrition

Customers with extended inactivity periods were substantially more likely to churn.

The data suggests that proactive intervention should occur before customers become completely disengaged.

---

# 3. Premium Card Segments Experience Higher Churn

Gold and Platinum card holders demonstrated higher churn rates than other card categories.

This indicates potential opportunities for premium customer loyalty programs.

---

# 4. Revenue Risk is Concentrated in Specific Segments

Although some segments have lower churn percentages, their large customer base creates significant revenue exposure.

Retention strategies should prioritize revenue impact rather than churn percentage alone.

---

## Business Recommendations

# Recommendation 1

Implement an inactivity monitoring program that flags customers before they become long-term inactive.

# Recommendation 2

Use transaction frequency as a customer health indicator for retention campaigns.

# Recommendation 3

Develop targeted loyalty initiatives for premium card customers.

# Recommendation 4

Prioritize retention efforts on segments contributing the highest revenue at risk.

# Recommendation 5

Create automated customer engagement campaigns for customers showing early signs of disengagement.

---

## Dashboard Preview

# Executive Dashboard

**Dashboard**:-https://github.com/unnadaditya-bot/Fintech-Customer-Churn-Retention-Analytics/blob/main/Dashboard_Overview.png

# Insights & Recommendations

Insights:-https://github.com/unnadaditya-bot/Fintech-Customer-Churn-Retention-Analytics/blob/main/Insights%20%26%20Recommendations.png

### SQL Analysis

SQL Queries:-https://github.com/unnadaditya-bot/Fintech-Customer-Churn-Retention-Analytics/blob/main/sql_queries.png

### SQL Results

SQL Results:-https://github.com/unnadaditya-bot/Fintech-Customer-Churn-Retention-Analytics/blob/main/sql_query_results.png

---

## Repository Structure

fintech-customer-churn-analysis/
│
├── README.md
│
├── Dashboard/
│   ├── Customer_Churn_Dashboard.xlsx
│
├── SQL/
│   └── sql_queries.sql
│
├── Dataset/
│   └── BankChurners.csv
│
└── Screenshots/
    ├── dashboard_overview.png
    ├── insights_recommendations.png
    ├── sql_queries.png
    └── sql_results.png

---

## Skills Demonstrated

* SQL
* MySQL
* Data Cleaning
* Customer Analytics
* Churn Analysis
* KPI Development
* Excel Dashboard Design
* Data Visualization
* Business Intelligence
* Business Recommendations
* Analytical Thinking

---

## Author

**Aditya Unnad**

BBA Graduate | Aspiring Data Analyst
LinkedIn: https://www.linkedin.com/in/aditya-h-unnad

This project demonstrates how customer behavior, transaction activity, and engagement metrics can be translated into actionable retention strategies using SQL and Excel.
