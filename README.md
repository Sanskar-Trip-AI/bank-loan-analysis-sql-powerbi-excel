# Bank Loan Analysis (SQL + Power BI + Excel)

This project focuses on analyzing bank loan data to identify key trends, assess lending performance, and evaluate risk patterns. Using SQL for data processing and Power BI for visualization, the project highlights insights that support data-driven lending decisions.

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Dataset Description](#dataset-description)
- [Tools & Technologies Used](#tools--technologies-used)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Dashboard Overview](#dashboard-overview)
- [SQL Approach](#sql-approach)
- [Insights & Observations](#insights--observations)
- [Reports & Deliverables](#reports--deliverables)
- [Conclusion](#conclusion)

## Project Overview
The goal of this project is to perform an end-to-end analysis of loan data from a financial institution. The analysis covers loan disbursement trends, borrower profiles, interest rates, and repayment performance. Results are visualized in Power BI to provide actionable insights for risk assessment and business decision-making.

## Objective
- To analyze overall loan performance and borrower behavior.
- To classify loans into 'Good' and 'Bad' categories based on repayment.
- To study relationships between interest rate, loan amount, and income.
- To visualize insights that help stakeholders improve lending strategies.

## Dataset Description
- **Source:** Open-source bank loan dataset (approx. 38,000 records, 24–25 columns)
- **Key Columns:** loan_id, purpose, funded_amount, interest_rate, dti, annual_income, loan_status, issue_date
- **Cleaning & Processing:** Missing value handling, date extraction, data type conversions


## Tools & Technologies Used
- **SQL:** Data cleaning, transformation, and aggregation
- **Power BI:** Interactive dashboards and KPIs
- **Excel:** Exploratory analysis and data validation

## Key Performance Indicators (KPIs)
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)
- % of Good Loans vs. Bad Loans


## 📊 Dashboards Overview

The project includes three interactive Power BI dashboards — **Summary**, **Overview**, and **Details** — designed to analyze and visualize loan performance and borrower data effectively.

---

### 🧮 Summary Dashboard
![Summary Dashboard](dashboard/Summary.png)

The **Summary Dashboard** captures key loan-related metrics and their changes over time, providing a snapshot of the loan portfolio's overall health and lending strategy impact.  
It includes the following KPIs:
- **Total Loan Applications (MTD and MoM)**
- **Total Funded Amount (MTD and MoM)**
- **Total Amount Received (MTD and MoM)**
- **Average Interest Rate (MTD and MoM)**
- **Average Debt-to-Income Ratio (DTI) (MTD and MoM)**  
Additionally, it distinguishes between *Good Loans* and *Bad Loans*, with specific indicators for each category — helping assess loan portfolio quality.

---

### 🌐 Overview Dashboard
![Overview Dashboard](dashboard/Overview.png)

The **Overview Dashboard** visually represents various loan-related metrics through multiple chart types:
- **Monthly Trends by Issue Date**
- **Regional Analysis by State**
- **Loan Term Analysis**
- **Employment Length Analysis**
- **Loan Purpose Breakdown**
- **Home Ownership Analysis**  
These visualizations help identify trends, seasonal patterns, and the distribution of loans across multiple borrower and loan characteristics.

---

### 🗂️ Details Dashboard
![Details Dashboard](dashboard/Details.png)

The **Details Dashboard** provides a granular, user-friendly view of all loan data for in-depth analysis of borrower profiles and performance metrics.  
Key data fields include:
- Loan ID, Address State, Employment Length, Employee Title  
- Grade/Sub Grade, Home Ownership, Issue Date, Loan Status  
- Purpose, Term, Verification Status, Annual Income  
- DTI, Instalment, Interest Rate, and Loan Amount  

Each field plays a critical role in loan management, risk assessment, and data-driven decision-making.
