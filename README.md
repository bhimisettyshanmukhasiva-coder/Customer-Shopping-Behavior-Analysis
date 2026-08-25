# Customer Shopping Behavior Analysis

## Project Overview

This project is about analyzing customer shopping behavior and finding useful patterns from customer purchase data.

I worked on this project step by step, starting with data exploration and cleaning using Python and Pandas. After cleaning the data, I loaded it into PostgreSQL and used SQL queries to answer business-related questions. Finally, I connected the PostgreSQL database to Power BI and created an interactive dashboard.

## Objective

The main objective of this project is to understand customer purchasing patterns and identify useful insights from the data.

The analysis focuses on:

- Customer purchasing behavior
- Purchase amount
- Product categories
- Age groups
- Gender
- Subscription status
- Shipping type
- Purchase frequency
- Discount usage
- Customer ratings and reviews

## Tools and Technologies

- Python
- Pandas
- PostgreSQL
- SQL
- Power BI
- GitHub

## Project Workflow

### 1. Data Exploration and Cleaning

I first loaded the dataset into Python and explored the data using Pandas.

Some of the checks performed were:

- `head()`
- `tail()`
- `shape`
- `columns`
- `info()`
- `dtypes`
- `describe()`
- Missing value checks
- Duplicate checks
- Unique value checks
- `value_counts()`

After understanding the dataset, I cleaned and prepared the data for further analysis.

### 2. PostgreSQL

After cleaning the data, I loaded it into PostgreSQL.

**Database:** `customer_behavior`

**Table:** `customer_shopping`

PostgreSQL was used to store the cleaned data and perform SQL analysis.

### 3. SQL Analysis

I created SQL queries to answer business questions related to customer shopping behavior.

The analysis included:

- Customer count
- Purchase amount
- Product category analysis
- Customer segments
- Subscription behavior
- Shipping preferences
- Purchase frequency
- Discount usage
- Customer ratings and reviews

### 4. Power BI Dashboard

I connected the PostgreSQL database to Power BI Desktop using Import mode.

The dashboard contains KPI cards, charts, and slicers to make the analysis interactive.

### Key KPIs

| KPI | Value |
|---|---:|
| Total Customers | 3.9K |
| Average Purchase Amount | $59.76 |
| Average Review Rating | 3.75 |

The dashboard also provides analysis based on category, age group, subscription status, gender, and shipping type.



