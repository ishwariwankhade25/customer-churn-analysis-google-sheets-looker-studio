# Customer Churn Analysis – SaaS Subscription Insights

An end to end customer churn analysis project that identifying key churn drivers, quantifies revenue impact, and delivers actionable retention strategies using real world telecom SaaS data.

## Table of Contents

- [Overview](#Overview)
- [Problem Statement](#Problem-Statement)
- [Dataset](#Dataset)
- [Tools and Technologies](#Tools-and-Technologies)
- [Methods](#Methods)
- [Key Insights](#Key-Insights)
- [Dashboard / Output](#Dashboard--Output)
- [How to Run This Project](#How-to-Run-This-Project)
- [Results & Conclusion](#Results--Conclusion)
- [Future Work](#Future-Work)
- [Author](#Author)

## Overview

Customer churn is one of the most critical challenges for subscription-based businesses. This project analyzes customer behavior to understand why customers leave, which segments are most at risk, and how churn impacts revenue.

## Problem Statement

The business is facing a high customer churn rate that directly impacts recurring revenue and growth.
This project aims to identify churn drivers, quantify revenue loss, and provide data-driven recommendations to improve customer retention.

## Dataset

This project uses the Telco Customer Churn dataset, widely used for churn analysis in subscription based businesses.

### Original Dataset (Raw Data)

- **Source:** Kaggle
- **Dataset Name:** Telco Customer Churn

You can find the [origina dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) here.

The original dataset contains customer level data including demographic, service usage, contract types, billing information, and churn status.

### Cleaned Dataset

#### Key Columns Added During Cleaning
- `Tenure Group` – Categorized customer tenure (New, Medium, Long)<br>
- `Monthly Charge Group` – Binned monthly charges (Low, Medium, High)<br>
- `Churn_Numeric` – Binary churn flag (1 = Churned, 0 = Active)<br>
- `SeniorCitizenText` – Readable senior citizen indicator

**Location:** `Clean Data - churn_data.csv`<br>
**Direct Link:** [Clean dataset use for analysis ](https://github.com/<ishwariwankhade25>/customer-churn-analysis-looker/blob/main/data/clean/churn_data_clean.csv)

### Key Features:

- Customer tenure & tenure groups
- Contract type
- Monthly charges & charge groups
- Internet service type
- Churn indicator (Yes/No)
- Revenue related attributes

## Tools and Technologies

**Google Sheets** – Data cleaning and transformation
**Looker Studio** – Dashboard development

## Methods

Data cleaning and validation

#### KPI calculation:

- Total Customers
- Customers Churned
- Overall Churn Rate
- Average Monthly Charges
- Revenue Lost due to Churn

Business insight generation

## Key Insights

- Month to month contracts drive the highest churn
- Churn risk is highest during the first year
- Higher monthly charges correlate with increased churn
- Fiber optic users churn more than DSL and non internet users
- Long term contracts significantly improve retention

## Dashboard / Output

The Looker Studio dashboard presents:

- Executive KPI cards
- Interactive filters
- Churn breakdown by customer segment
- Revenue impact visualization

**Dashboard:** [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/b1300551-bc5b-4632-90dd-51b3be5ddd77)

![Dashboard](https://github.com/user-attachments/assets/0266a90c-1d30-4d32-b1ee-755f906f6fee)


## How to Run This Project

- Download the dataset from Kaggle (link provided)
- Review the cleaned dataset included in this repository
- Open the Looker Studio dashboard
- Connect the cleaned dataset if recreating the dashboard
- Explore insights using interactive filters

## Results & Conclusion

- Overall churn rate: 26.54%
- Revenue lost due to churn: $139,131
- New customers and flexible contracts represent the highest churn risk

#### Targeted onboarding, pricing strategies, and contract optimization can significantly reduce churn.

## Future Work

- Develop predictive churn models
- Calculate Customer Lifetime Value (CLV)
- Integrate behavioral and usage data
- Automate churn monitoring dashboards

## Author

Ishwari Wankhade<br>
Aspiring Data Analyst | Business Intelligence | Analytics
- 📧 **Email:** [career.ishwari@gmail.com](career.ishwari@gmail.com)
- 🔗 **LinkedIn:** [LinkedIn](linkedin.com/in/ishwari-analytics)

