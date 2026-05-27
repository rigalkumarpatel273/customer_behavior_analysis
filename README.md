Project Title: Customer Behavior Analysis

Overview
This end-to-end data analytics project demonstrates how to transform raw, unstructured data into actionable business insights. The project spans the entire data lifecycle: from Python-based data ingestion and cleaning, to SQL database management, and finally to interactive Power BI dashboards and executive presentations.

The primary business objective of this project is to analyze sales performance across demographics, marketing ROI on different types of shipments used and subsciption impacts on revenue and provide data-driven recommendations to stakeholder teams.

Dataset
Source: customer_shopping_behavior.csv

Size: 3900rows, 19 columns

Description: The dataset contains historical records of retail transactions of customers online shopping among different age groups.

Tech Stack & Tools
Data Ingestion & EDA: Python (Pandas, sqlalchemy, psycopg-2)

Database Management: PostgreSQL

Data Visualization & Modeling: Power BI

Reporting & Presentation: Gamma AI (Presentation), Microsoft Word/Markdown (Report)

Project Steps
1. Data Loading & Exploratory Data Analysis (EDA)
Imported the raw dataset using Python.

Conducted initial EDA to check data distributions, identify missing values, and locate outliers using Seaborn and Matplotlib.

Notebook: notebooks/eda_and_cleaning.ipynb

2. Data Cleaning & Transformation
Handled missing values via fillna and corrected inconsistent data types.

Removed duplicate records and filtered out statistical anomalies.

Exported the cleaned dataset as a structured CSV file ready for database relational mapping.

3. SQL Database Ingestion & Querying
Designed the database schema and imported the cleaned data into PostgreSQL.

Wrote optimized SQL queries to extract deep-dive insights, including:

  Aggregations and trend analyses.
  Joins across tables (if applicable).
  Scripts: sql_queries/analysis_queries.sql

4. Power BI Dashboarding
Connected Power BI to the SQL database.

Built a robust data model using Power Query for final transformations.

Developed custom business metrics using DAX (Data Analysis Expressions).

Designed an interactive, single-page dashboard focused on user experience (UX) and executive scannability.

Dashboard Preview
customer_behavior_dashboard

<img width="581" height="325" alt="dashboard" src="https://github.com/user-attachments/assets/9f63e761-a012-48fd-9c7a-b137767f0577" />

Key Features: Average purchase amount, average review rating, Revenue by Category, Sales by Category, % of customers by subscription status.

Results & Insights
Based on the SQL analysis and Power BI visualizations, the following key business insights were uncovered:

Average purchase amounts: $59.76
Average review rating: 3.75
Total number of customers: 3.9K

Strategic Recommendation:
Boost Subscriptions: Promote exclusive benefits for subscribers.

Customer Loyalty Programs: Reward repeat customers to move them into "Loyal" segment.

Review Discount Policy: Balance sales boosts with margin control.
