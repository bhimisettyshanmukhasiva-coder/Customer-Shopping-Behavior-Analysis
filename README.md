Customer Shopping Behavior Analysis

Project Overview

This project analyzes customer shopping behavior using Python, SQL,
PostgreSQL, and Power BI.

I worked on the project step by step, starting with understanding and
cleaning the dataset in Python. After preparing the data, I loaded it
into PostgreSQL and used SQL queries to answer business-related
questions. Finally, I connected the PostgreSQL database to Power BI and
created a dashboard to present the analysis in a simple and interactive
way.

Objective

The main objective of this project is to understand customer purchasing
patterns and identify useful insights from the shopping data.

The analysis focuses on areas such as:

Customer purchasing behavior

Purchase amount

Product categories

Age groups

Gender

Subscription status

Shipping type

Purchase frequency

Discount usage

Customer reviews and ratings

Tools Used

Python -- Data exploration and preparation

Pandas -- Data cleaning and analysis

PostgreSQL -- Database storage

SQL -- Business analysis

Power BI -- Dashboard and visualization

GitHub -- Project documentation and portfolio

Project Workflow

1. Data Exploration and Cleaning

I first loaded the dataset into Python and explored its structure using
Pandas.

Some of the checks performed were:

head()

tail()

shape

columns

info()

dtypes

describe()

Missing-value checks

Duplicate checks

Unique-value checks

value_counts()

After understanding the dataset, I cleaned and prepared the data for
further analysis.

2. PostgreSQL

The cleaned data was loaded into a PostgreSQL database.

Database: customer_behavior

Main table: customer_shopping

PostgreSQL was used to store the cleaned data and make it easier to
perform structured SQL analysis.

3. SQL Analysis

I created SQL queries to answer business questions related to customer
shopping behavior.

The analysis included areas such as:

Customer counts

Purchase amounts

Product categories

Customer segments

Subscription behavior

Shipping preferences

Purchase frequency

Discount usage

Ratings and reviews

4. Power BI Dashboard

The PostgreSQL database was connected to Power BI Desktop using Import
mode.

The dashboard contains KPI cards, charts, and slicers that allow the
data to be explored interactively.

Key KPI Measures

KPI                           Value

Total Customers                3.9K
Average Purchase Amount     $59.76
Average Review Rating          3.75

The dashboard also contains analysis by category, age group,
subscription status, and other customer-related dimensions.

Dashboard

The Power BI dashboard is included in the PowerBI folder.

A dashboard screenshot can be found in the Images folder.

Repository Structure

Customer-Shopping-Behavior-Analysis/
│
├── README.md
│
├── Python/
│   └── Customer_Shopping_Analysis.ipynb
│
├── SQL/
│   └── Customer_Shopping_Analysis.sql
│
├── PowerBI/
│   └── Customer_Shopping_Behavior_Analysis.pbix
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Images/
│   └── dashboard.png
│
└── Documentation/
    └── Customer_Shopping_Behavior_Project_Documentation.docx

What I Learned

Through this project, I learned how to work on an analytics project from
beginning to end instead of using only one tool.

Some of the main things I practiced were:

Exploring data using Python and Pandas

Identifying and cleaning data-quality issues

Writing SQL queries for business questions

Working with PostgreSQL

Connecting a database to Power BI

Creating DAX measures

Designing Power BI visuals

Using slicers for interactive analysis

Presenting an analytics project on GitHub

Future Improvements

Some possible improvements for the project are:

Add more advanced DAX measures

Add more detailed product-level analysis

Create additional customer segmentation

Add more business recommendations

Improve dashboard formatting based on feedback

Add more interactive Power BI pages if required

Author

Bhimisetty Shanmukha Siva Ganesh

B.Tech -- Electronics & Communication Engineering
Specialization: Nanotechnology and Opto-Electronics
KL University
Graduation: 2027
CGPA: 9.05
Mobile: 9392577069
