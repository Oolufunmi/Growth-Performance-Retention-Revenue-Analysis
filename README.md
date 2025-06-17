# Growth-Performance-Retention-Revenue-Analysis

A Cohort-Based Growth and Revenue Analysis for a Financial Services Company, using Monthly Active Users (MAU), Average Revenue Per User (ARPU), and Retention Metrics to uncover Performance Trends.

## 📚 Table of Contents

1. [Overview](#-overview)  
2. [Data Sources](#-data-sources)  
3. [Additional Dataset Information & Case Study context](#-aditional-information-about-the-dataset--casestudy-context)  
4. [Growth Analyst Case Study context](#-growth-analyst-case-study-context)  
5. [Instructions](#-instructions)  
6. [Project Files](#-project-files)  
7. [Key KPIs Analyzed](#-key-kpis-analyzed)  
8. [Tools & Approach](#-tools--approach)  
9. [Key Insights](#-key-insights)  
10. [Recommendations](#-recommendations)  
11. [Author](#-author)


## 📊 Overview

This repository contains my analysis of the Growth Data Analyst Case Study, focused on analyzing user and business performance across a 16-month period.

The objective was to identify the most impactful KPIs that reflect business growth, user retention, and marketing effectiveness. The analysis was performed using two datasets:

- `01_signup.csv`: Ad spend, installs, accounts created
- `02_monthly_performance.csv`: MAUs, transactions, revenue

---

## 📂 Data Sources

### `data/01_signup.csv`

- Monthly ad spend, app installs, and account creation figures.
- Used to assess marketing efficiency and acquisition trends.

### `data/02_monthly_performance.csv`
- Cohort-based user activity data including MAUs, transactions, and revenue.
- Used for retention analysis, ARPU calculation, and transaction trends.

---
### Additional Dataset Information & Case Study Context
  two primary datasets were used for this Growth Data Analysis case study:

- 01_signup.csv: Contains monthly digital ad spend, app installs, and new accounts created.
- 02_monthly_performance.csv: Contains monthly user activity metrics, revenue, transaction count, and cohort-based MAUs.

The data spans a 16-month period and will be used to derive key KPIs such as MAU, ARPU, retention rate, and transaction value.
# 📄 Growth Analyst Case Study Context

As a Growth Data Analyst, you have been tasked with understanding the performance of our marketing spend, as well as general business performance. There are 2 sources of information that are available to you, namely:

### 01_signup
Schema:
- `month`: The reporting month.
- `spend_usd`: Total spend on digital ads (in $).
- `n_installs`: The number of installs in the reporting month.
- `n_accounts_created`: The number of accounts created in the reporting month.

### 02_monthly_performance
Schema:
- `transaction_month`: The transaction (reporting) month.
- `account_created_cohort_month`: The month in which the user’s account was created.
- `n_maus`: The number of Monthly Active Users (MAUs).
- `total_revenue_usd`: The total revenue (in USD) accrued.
- `n_transactions`: The total count of transactions completed.
- `total_transaction_value_usd`: The total volume (in USD) of the transactions completed.

---

### 📌 Instructions

The management team has asked you to analyze the data and share key insights into the business performance.  
**What would be your top 4 KPIs you would present to the team?**

Please prepare a short presentation/document that highlights:
- What these 4 KPIs are
- Why you’ve chosen them (as a Growth Data Analyst)
- How you calculated them
- The outcome of these KPIs

**[Bonus]**  
We are interested in understanding the average retention rate of our MAUs — are you able to uncover this?

---

### 📝 Notes
- The data is completely random and provides a 16-month snapshot.
- You will be able to pull many metrics from the dataset(s), but the main objective is to highlight the **most important** ones (and why).
- We recommend spending no more than **4–5 hours** on this.





## 📄 Project Files

- 📘 [User Performance Report.June 2025.pdf](#User Performance Report.June 2025.pdf)
- 📊 [01 Signup Data (CSV)](./data/01_signup.csv)
- 📈 [02 Monthly Performance Data (CSV)](./data/02_monthly_performance.csv)

---

## ✅ Key KPIs Analyzed

1. **Monthly Active Users (MAUs)** – Core growth metric
2. **ARPU (Average Revenue Per User)** – Monetization efficiency
3. **Total Transaction Value** – Platform usage depth
4. **Marketing Spend Efficiency** – % change in ad spend vs MAU growth
5. **[Bonus] Retention Rate** – Cohort stickiness across months

---
- Report
  [User Performance Report.June 2025.pdf](https://github.com/user-attachments/files/20777984/User.Performance.Report.June.2025.pdf)

## ⚙️ Tools & Approach

- Data visualization (Tableau/Excel)
- Metric calculations
- Cohort analysis
- Business storytelling

---

## 📌 Key Insights

- MAUs and ARPU showed strong, consistent growth
- Retention improved in newer cohorts
- Ad spend volatility didn’t always correlate with growth

---

## ✅ Recommendations

- Focus on ARPU-driving initiatives
- Optimize first-month retention
- Stabilize marketing investment for better ROI

---

## 📬 Author

**Olufunmilola Olapeju Olaewe**  
_MSc Statistics | Growth Data Analyst_  
📧 olufunmilolaolapejuolaewe@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/olufunmilolaolaewe/)
