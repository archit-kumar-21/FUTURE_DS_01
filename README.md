Superstore Sales Analysis Dashboard
Project Overview

This project analyzes a retail sales dataset to uncover business insights, revenue trends, and profitability patterns. The goal is to simulate the type of analysis a data analyst performs for businesses to help them make data-driven decisions.

The project involves:

Data cleaning and preprocessing using Python

Exploratory Data Analysis (EDA) to identify trends and patterns

Building an interactive business dashboard using Microsoft Power BI Desktop

Generating insights and actionable recommendations for business growth

This project demonstrates real-world analytics workflow, from raw data to decision-making dashboards.

Dataset

Dataset used: Superstore Sales Dataset

Source:
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset contains retail order information such as:

Order Date
Product Category
Sub-Category
Region
Sales
Profit
Discount
Quantity

It represents transactions from a fictional retail store.

Tools & Technologies Used
Tool	Purpose
Python	Data cleaning & EDA
Pandas	Data manipulation
Matplotlib / Seaborn	Data visualization
Microsoft Power BI Desktop	Interactive dashboard creation
GitHub	Project documentation and version control
Project Workflow
1. Data Cleaning (Python)

Steps performed:

Loaded raw CSV dataset
Checked missing values
Removed duplicates
Converted date columns to proper datetime format

Created new features such as:

Year
Month
Month Name

Exported cleaned dataset for dashboard use

Output file:
data/cleaned/SuperstoreCleaned.csv

2. Exploratory Data Analysis (EDA)

Key analyses performed:
Sales Trend Over Time
Analyzed revenue growth across time periods to detect trends and seasonality.

Category Performance

Identified which product categories generate the highest revenue.
Regional Profitability
Compared profit generated across regions.
Discount vs Profit Relationship
Examined how discounts impact profitability.
Top Selling Products
Identified products contributing most to total revenue.

                       Power BI Dashboard

An interactive business dashboard was built using the cleaned dataset.

Page 1 – Executive Overview
Key metrics displayed:
Total Sales
Total Profit
Total Orders
Average Discount

Visualizations:
Sales Trend Over Time
Sales by Category
Profit by Region
Interactive filters for Region, Category, and Year

Page 2 – Product Analysis
Insights on product performance:
Top 10 Products by Sales
Sales by Sub-Category
Quantity Sold by Category

Page 3 – Regional Insights
Geographical sales performance analysis:
Sales Map by State
Regional Sales Distribution
Profit Comparison by Region

                    Key Business Insights

Some insights derived from the analysis:

Technology category generates the highest revenue.
West region produces the highest overall profit.
Higher discounts tend to reduce profit margins.
Certain products have high sales but low profitability due to heavy discounting.
Sales show seasonal spikes during certain months.
                   
                   Business Recommendations
Based on the analysis:
Reduce excessive discounting on low-margin products
Focus marketing on high-performing product categories
Increase sales efforts in highly profitable regions
Improve pricing strategy for products with high sales but low profit

Project Structure
Superstore-Sales-Analysis
│
├── data
│   ├── raw
│   │   └── SuperstoreRaw.csv
│   └── cleaned
│       └── SuperstoreCleaned.csv
│
├── notebooks
│   └── sales_analysis.ipynb
│
├── dashboard
│   └── superstore_dashboard.pbix
│
├── images
│   ├── executive_dashboard.png
│   ├── product_analysis.png
│   └── regional_insights.png
│
└── README.md

                    Example Dashboard

![alt text](<images/1Executive 1 Dasboard.png>) ![alt text](<images/2Executive 2 Dashboard.png>) ![alt text](<images/3Regional Dashboard.png>) ![alt text](<images/4Product Analysis Dashboard.png>)



                   Skills Demonstrated

This project highlights several important data analytics skills:

Data cleaning and preprocessing
Exploratory data analysis
Business KPI analysis
Data storytelling
Dashboard design
Business insight generation

These skills are essential for Data Analyst and Business Intelligence roles.

                  Future Improvements
Potential extensions of this project:

Customer segmentation analysis
Sales forecasting using machine learning
Profit margin optimization models
Customer lifetime value analysis


Author

ARCHIT KUMAR

GitHub:
https://github.com/archit-kumar-21

LinkedIn:
https://www.linkedin.com/in/architkumar21/
