# E-Commerce Customer Churn Analysis

---

# Objective

This project analyzes e-commerce customer churn data using MySQL to identify customer behavior patterns, churn factors, and business insights.

The main objectives of this project are:

- Analyze customer churn behavior
- Identify factors influencing customer retention
- Understand customer purchase and engagement patterns
- Perform data cleaning and transformation using SQL
- Generate meaningful business insights through SQL analysis

---

# Dataset Information

- Domain: E-Commerce
- Database: MySQL
- Dataset Type: Customer Churn Data
- Total Columns: 20

## Key Columns

- CustomerID
- Churn
- Tenure
- PreferredLoginDevice
- CityTier
- WarehouseToHome
- PreferredPaymentMode
- Gender
- HourSpendOnApp
- NumberOfDeviceRegistered
- PreferedOrderCat
- SatisfactionScore
- MaritalStatus
- NumberOfAddress
- Complain
- CouponUsed
- OrderCount
- DaySinceLastOrder
- CashbackAmount

---

# Tools Used

## MySQL

Used for:

- Database creation
- Table creation
- Data insertion
- Data cleaning
- Data transformation
- Data analysis
- Query execution

---

# Database Creation

The following operations were performed:

- Created database named `ecomm`
- Created customer_churn table
- Defined primary key for CustomerID
- Assigned appropriate data types for columns
- Inserted customer churn dataset into MySQL table

---

# Data Cleaning and Preparation

The following preprocessing steps were performed:

- Handled missing values
- Standardized payment mode values
- Corrected inconsistent text values
- Validated numeric and categorical columns
- Improved data consistency for analysis
- Structured the dataset for business reporting

---

# SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- INSERT INTO
- PRIMARY KEY
- WHERE
- GROUP BY
- ORDER BY
- CASE WHEN
- COUNT
- AVG
- SUM
- MAX
- MIN
- JOIN
- Aggregate Functions

---

# Analysis Performed

The project includes analysis on:

- Customer churn distribution
- Customer satisfaction levels
- Preferred payment methods
- Order behavior patterns
- Cashback and coupon usage
- Device usage analysis
- Complaint analysis
- Customer tenure analysis
- Product category preferences

---

# Key Insights

- Customers with lower satisfaction scores show higher churn rates
- Customers with complaints are more likely to churn
- Mobile phone users form a large portion of the customer base
- Cashback and coupon usage influence customer engagement
- Certain product categories have higher customer retention
- Frequent order customers tend to have lower churn rates

---

# Conclusion

This project demonstrates the practical application of MySQL for database management, data cleaning, transformation, and customer churn analysis.

The analysis helps identify important customer behavior patterns and provides meaningful business insights that support customer retention strategies and data-driven decision-making.
