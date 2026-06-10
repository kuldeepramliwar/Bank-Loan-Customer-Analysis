# Bank Loan Customer Analysis

# Project Overview

A comprehensive data analysis project analyzing **39,717 bank loan records** across 8 years (2007-2014). Built interactive dashboards in **Excel, Power BI, and Tableau**. Replicated all analysis using **SQL queries** in MySQL.

# Business Problem

Banks need to quickly understand:
- Loan performance patterns across years
- Customer payment behaviors by region
- Default risks by loan grade and verification status
- Geographic concentration of loans
- Home ownership impact on repayment

# Key Metrics

| Metric               | Value     |
|----------------------|-----------|
| Total Loans Analyzed | 39,717    |
| Total Funded Amount  | ₹445.60 M |
| Average DTI Ratio    | 13.32%    |
| Average Loan Value   | ₹11,219   |
| Default Rate         | 17.4%     |
| Time Period          | 2007-2014 |

# 5 Core KPIs Built

1. **Year-wise Total Loan Amount** - Shows loan growth trend over 8 years
2. **Grade & Sub-Grade Revolving Balance** - Analyzes credit quality distribution
3. **Total Payment by Verification Status** - Compares payment amounts across verification levels
4. **State-wise Loan Status** - Maps loan distribution across USA states
5. **Home Ownership vs Last Payment Amount** - Shows payment behavior by home ownership type

# Tools & Technologies

| Tool         | Purpose                                  |
|--------------|------------------------------------------|
| **Excel**    | Data cleaning, Pivot Tables, Dashboard   |
| **Power BI** | Interactive dashboards with DAX measures |
| **Tableau**  | Professional visualizations              |
| **MySQL**    | SQL queries for all 5 KPIs               |

# Project Structure 

# Key Insights Discovered

# Loan Growth Trend
- Loans grew from ₹2.2M (2007) to ₹260.51M (2012) — a **118x increase**
- Peak lending year: 2012

# Customer Credit Quality
- Grade A customers maintain highest revolving balances
- Verified customers show strongest payment behavior
- Source Verified loans: ₹219.89M total payments
- Not Verified loans: ₹109.27M total payments

# Geographic Patterns
- California and New York dominate loan distribution
- Geographic risk varies significantly by state
- Concentration risk identified in top 5 states

# Home Ownership Impact
- Mortgage holders show strongest repayment behavior
- Renters have lower payment amounts
- Home ownership is strong indicator of creditworthiness

# Skills Demonstrated

**Data Analysis**
- Cleaned and transformed 39,717 messy records
- Handled missing values and date format issues
- Created meaningful KPIs from raw data

**SQL Expertise**
- INNER JOIN to connect two tables
- SUBSTRING function for date extraction
- GROUP BY and aggregate functions (SUM, COUNT, AVG)
- Optimized query writing

**Dashboard Design**
- Interactive filters and slicers
- Multi-chart visualizations
- Professional color schemes
- Clear data storytelling

**Tool Proficiency**
- Excel: Pivot Tables, formulas, conditional formatting
- Power BI: DAX measures, relationships, filters
- Tableau: Calculated fields, geographic analysis
- MySQL: Database creation, complex queries

# How to Use This Repository

1. **View SQL Queries** → Go to `SQL_Queries/` folder
2. **database** → `database/` folder
3. **See Dashboards** → View screenshots in `Dashboard_Screenshots/`
4. **Run Queries** → Use MySQL with provided database setup file

# To Run SQL Queries:

```sql
-- Create database
CREATE DATABASE BANK_LOAN_STATUS;
USE BANK_LOAN_STATUS;

-- Load data and run queries from SQL_Queries folder
