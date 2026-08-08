# Credit Card Financial Analytics

An end-to-end analytics project examining credit card customer profiles, spending behavior, revenue, and financial risk indicators, built on **PostgreSQL** and **Power BI**.

**Tools:** PostgreSQL 17 · SQL (DDL + DML) · Power BI Desktop · DAX

---

## Overview

This project analyzes a credit card portfolio across four dimensions:

1. **Customer Demographics** — age, income, gender, and satisfaction profile of the customer base
2. **Transaction Behavior** — spending trends, transaction volume, and expenditure categories
3. **Revenue & Profitability** — interest income, fee revenue, and performance by card category
4. **Risk & Delinquency** — utilization, revolving balances, and delinquency patterns by customer segment

---

## Key Metrics

| Area | Metric | Value |
|---|---|---|
| Customers | Total Customers | 10,293 |
| Customers | Avg. Customer Age | 46 yrs |
| Customers | Avg. Income | $57K |
| Customers | Satisfaction Score | 3.2 / 5 |
| Transactions | Total Transaction Amount | $45.5M |
| Transactions | Total Transactions | 656K |
| Transactions | Avg. Transaction Value | $69.4 |
| Revenue | Total Revenue | $8.6M |
| Revenue | Interest Earned | $3.0M |
| Revenue | Annual Fee Revenue | $2.4M |
| Revenue | Total Acquisition Cost | $1.0M |
| Risk | Delinquent Accounts | 2,253 |
| Risk | Delinquency Rate | 21.9% |
| Risk | Avg. Utilization | 27.3% |
| Risk | Total Revolving Balance | $12.5M |

---

## Methodology

1. **Data Ingestion** — Raw CSV files loaded into PostgreSQL 17 using the `COPY` command with `datestyle` configuration
2. **Data Cleaning** — Duplicate removal via `ctid`-based SQL, NULL handling, and date format standardization
3. **Data Modeling** — Relational schema with `cust_detail` and `cc_detail` tables joined on `Client_Num`
4. **Visualization** — Interactive Power BI dashboard with slicers, KPI cards, and drill-through capability

---

## Key Insights & Recommendations

- **Blue Card dominates revenue** — contributes 53% of total revenue; loyalty and upgrade programs can upsell customers to Silver/Gold tiers
- **Q4 drives peak transactions** — transaction volume spikes significantly in Q4, an opportunity for targeted promotional campaigns
- **Self-employed customers are highest risk** — show the highest delinquency rate; stricter credit screening and lower limits are recommended
- **Female customers are more active** — the female segment (53%) shows higher transaction frequency, an opportunity for gender-specific product bundling
- **Interest income drives profitability** — interest earned contributes $3M of $8.6M total revenue (35%); improving revolving balance management can boost profitability further
- **Bills & utilities lead spending** — the top expenditure category, representing an opportunity for EMI conversion product offerings

---

## Tech Stack

- **Database:** PostgreSQL 17
- **Query Layer:** SQL (DDL + DML)
- **BI Tool:** Power BI Desktop
- **Calculations:** DAX
- **Data Pipeline:** CSV → PostgreSQL → Power BI

---

## Contact

**Japdeep Singh**
GitHub: [github.com/Japdeep123](https://github.com/Japdeep123)
LinkedIn: [linkedin.com/in/japdeep-singh-15713b325](https://www.linkedin.com/in/japdeep-singh-15713b325/)

Open to questions, feedback, and collaboration.
