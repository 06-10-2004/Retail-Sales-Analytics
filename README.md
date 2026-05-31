# Retail Sales and Customer Analytics

![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-red)
![T-SQL](https://img.shields.io/badge/T--SQL-Analysis-blue)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## Project Overview

This project demonstrates how SQL Server and T-SQL can be used to transform raw retail sales data into actionable business insights.

The analysis focuses on customer behavior, revenue trends, product performance, customer retention, churn analysis, and customer segmentation. The project follows a structured SQL analytics workflow, starting from data cleaning and transformation to advanced business analysis and insight generation.

Excel was used only for importing raw datasets into SQL Server. All data cleaning, transformation, aggregation, and analysis were performed using T-SQL.

---

## Business Problem

Retail businesses generate large volumes of transactional data, but raw data alone cannot support strategic decision-making.

This project aims to:

- Clean and transform raw retail datasets into structured tables
- Analyze customer purchasing behavior
- Identify high-value customers
- Evaluate product performance
- Understand revenue and seasonal trends
- Measure customer retention and churn
- Provide recommendations for revenue growth and customer engagement

---

## Technology Stack

| Category | Tools |
|-----------|---------|
| Database | SQL Server |
| Query Language | T-SQL |
| Data Import | Microsoft Excel |
| Analysis | SQL-Based Business Analytics |
| Version Control | Git & GitHub |

---

## Data Structure

### customer_summary

Contains customer-level aggregated metrics.

**Key Columns**
- CustomerID
- Total Orders
- Total Quantity
- Total Spent
- First Purchase Date
- Last Purchase Date

**Business Metrics**
- Customer Lifetime Value (LTV)
- Retention Rate
- Repeat Purchase Rate
- Churn Analysis

---

### monthly_sales

Contains monthly revenue information.

**Key Columns**
- InvoiceMonth
- Monthly Revenue

**Business Metrics**
- Revenue Trends
- Seasonal Analysis
- Growth Tracking

---

### retail_cleaned

Cleaned transactional dataset.

**Key Columns**
- InvoiceNo
- StockCode
- Quantity
- UnitPrice
- TotalPrice
- Invoice_Date
- Invoice_Time
- InvoiceMonth

---

### retail_segmented

Customer segmentation dataset.

**Key Columns**
- CustomerID
- InvoiceNo
- Quantity
- UnitPrice
- TotalPrice
- Invoice_Date
- Invoice_Time

---

## Data Cleaning & Transformation

The following preprocessing steps were performed using T-SQL:

- Removed duplicate records
- Handled null and invalid values
- Standardized date formats
- Converted columns to appropriate data types
- Split datetime into separate date and time fields
- Created monthly revenue tables
- Built customer summary tables
- Generated segmented customer datasets

---

## Executive Summary

### Customer Loyalty
- Repeat Purchase Rate: **65.58%**
- Nearly two-thirds of customers make multiple purchases.

### Revenue Concentration
- Top 10 products contribute approximately **2% each** of total revenue.
- Revenue is concentrated among a small number of products.

### Seasonal Trends
- Highest monthly revenue occurred in **November 2011**
- Revenue peaked at approximately **₹1.49 Million**

### High-Value Customers at Risk
- Several top-spending customers have been inactive for over six months.
- These customers represent significant churn risk.

### Customer Activation
- Only **36.54%** of customers make their first purchase within 7 days.
- Average activation time is approximately **130 days**

---

## Key Insights

### Customer Retention
**Metric:** Repeat Purchase Rate

**Value:** 65.58%

**Insight:** A strong majority of customers return for additional purchases, indicating healthy customer loyalty and retention.

---

### Revenue Concentration
**Metric:** Product Revenue Contribution

**Value:** Top products contribute approximately 2% each.

**Insight:** A limited number of products drive a significant portion of overall revenue.

---

### Seasonal Revenue Trends
**Metric:** Monthly Revenue

**Value:** ₹1.49M Revenue (November 2011)

**Insight:** Sales activity peaks during the holiday season, making October–November critical periods for inventory and promotions.

---

### High-Value Customer Churn Risk
**Metric:** Inactive High-Spending Customers

**Insight:** Targeted retention campaigns can help preserve valuable customer relationships.

---

### Customer Activation Gap
**Metric:** Time to First Purchase

**Value:** 36.54% purchase within 7 days

**Insight:** Improving onboarding and engagement could accelerate customer conversion.

---

## Recommendations

- Launch loyalty programs for high-value customer segments
- Focus promotional campaigns during October and November
- Retain at-risk customers through personalized marketing
- Improve customer onboarding processes
- Review low-performing products for optimization
- Implement targeted retention strategies

---

## Project Workflow

```text
Raw Retail Data
       │
       ▼
Data Cleaning
       │
       ▼
Data Transformation
       │
       ▼
Customer Segmentation
       │
       ▼
Business Analysis
       │
       ▼
Insights & Recommendations
```

---

## Tools Used

### SQL Server
Primary platform used for:
- Data cleaning
- Data transformation
- Aggregation
- Business analytics

### T-SQL
Used for:
- Joins
- Window Functions
- Aggregations
- Customer Segmentation
- Churn Analysis
- Revenue Analysis

### Microsoft Excel
Used only for importing raw datasets into SQL Server.

---

## Caveats

- Churn is defined as no purchase activity within six months
- Revenue analysis does not include cost or profit information
- Some customers may have multiple same-day transactions
- Segmentation results depend on available customer data quality
- Findings are limited to the scope of the provided dataset

---

## Key Outcomes

- Built a complete SQL-based analytics workflow
- Measured customer retention and churn
- Identified high-value customer segments
- Analyzed product performance and revenue concentration
- Discovered seasonal sales trends
- Generated actionable business recommendations

---

## Conclusion

This project demonstrates how SQL Server and T-SQL can transform raw retail transaction data into meaningful business insights.

By analyzing customer behavior, revenue trends, product performance, and retention patterns, the project provides valuable recommendations that support strategic business decisions, improve customer engagement, and drive long-term revenue growth.

---

## Author

**HARITHA S**

Data Analyst | SQL Server
