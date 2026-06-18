# Customer Churn Analysis Dashboard

## Executive Summary

This project analyzes customer churn behavior for a telecom business to identify the factors driving customer attrition and provide data-driven recommendations for improving retention.

Using SQL and Power BI, the project transforms raw customer data into actionable business insights through data cleaning, exploratory analysis, KPI development, and interactive dashboarding.

---

# Business Problem

Customer churn directly impacts revenue growth, customer lifetime value, and profitability. The business required a comprehensive understanding of:

* Which customers are most likely to churn.
* What factors contribute to customer attrition.
* Which customer segments require retention interventions.
* How contracts, services, and customer behavior influence churn.

---

# Analytical Approach

### Data Preparation

* Analyzed 6,418 customer records.
* Performed data quality assessment and null-value treatment.
* Built a production-ready analytical dataset using SQL transformations.
* Created reusable reporting views for churn and customer lifecycle analysis.

### Dashboard Development

Developed a Power BI dashboard to analyze:

* Customer Demographics
* Geographic Distribution
* Contract Types
* Payment Methods
* Internet Services
* Customer Tenure
* Churn Categories
* Churn Reasons

---

# Key Business Findings

## 1. Customer Attrition

* Total Customers: 6,418
* Churned Customers: 1,732
* New Customers: 411
* Overall Churn Rate: 27%

### Insight

More than one out of every four customers has churned, indicating a significant retention challenge and potential revenue leakage.

---

## 2. Contract Type is the Strongest Predictor of Churn

| Contract Type  | Churn Rate |
| -------------- | ---------- |
| Month-to-Month | 46.5%      |
| One-Year       | 11.0%      |
| Two-Year       | 2.7%       |

### Insight

Customers with short-term commitments are significantly more likely to leave. Long-term contracts appear to be one of the strongest retention mechanisms.

### Recommendation

Introduce loyalty incentives and contract upgrade programs to encourage long-term commitments.

---

## 3. Fiber Optic Customers Represent the Highest Risk Segment

| Internet Type | Churn Rate |
| ------------- | ---------- |
| Fiber Optic   | 41.1%      |
| Cable         | 25.7%      |
| DSL           | 19.4%      |
| No Internet   | 7.8%       |

### Insight

Fiber Optic customers churn at a significantly higher rate than all other service groups, suggesting potential concerns related to pricing, expectations, or service quality.

### Recommendation

Conduct customer satisfaction analysis and review Fiber Optic pricing and service performance.

---

## 4. Competitor Pressure is the Largest Churn Driver

| Churn Category  | Customers |
| --------------- | --------- |
| Competitor      | 761       |
| Attitude        | 301       |
| Dissatisfaction | 300       |
| Price           | 196       |

### Insight

Approximately 44% of churned customers cited competitor-related reasons, indicating competitive offerings are having a direct impact on retention.

### Recommendation

Strengthen competitive positioning through pricing optimization, bundled services, and customer loyalty programs.

---

## 5. Geographic Retention Opportunities Exist

Highest churn rates observed in:

* Jammu & Kashmir – 57.2%
* Assam – 38.1%
* Jharkhand – 34.5%
* Chhattisgarh – 30.5%

### Insight

Customer churn varies significantly by region, suggesting location-specific market dynamics and service challenges.

### Recommendation

Develop targeted retention initiatives for high-risk regions.

---
https://github.com/Hussainsyedarshad/Customer_Churn_Analysis_mysql_python_ml_powerbi/blob/main/Screenshot%202026-06-18%20183530.png


---

# Summary

Analyzed 6,418 customer records using SQL and Power BI, resulting in the identification of 1,732 churned customers and uncovering the primary drivers of churn across contracts, services, customer tenure, and competitive factors.

---

## Tech Stack

* MySQL
* SQL
* Power BI
* DAX
* Power Query

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* SQL Development
* Data Modeling
* KPI Development
* Business Intelligence
* Dashboard Design
* Customer Analytics
* Data Storytelling
* Strategic Business Analysis
