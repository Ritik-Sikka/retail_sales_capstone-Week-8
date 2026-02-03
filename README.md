Retail Sales Optimization – Capstone Project
Project Overview

This project presents an end-to-end business analysis of retail sales data to identify key revenue drivers, customer behavior patterns, and strategic opportunities for profitability improvement. The objective was to simulate a real-world consulting scenario where raw data is transformed into actionable business insights using statistical analysis and machine learning techniques.

The project covers the complete analytics workflow including data cleaning, exploratory data analysis (EDA), regression modeling, clustering, and business implementation planning.

Business Problem

The retail organization lacks structured insights into:

Revenue growth drivers

Regional performance variations

Customer segmentation strategy

Data-driven decision-making framework

This project aims to provide analytical clarity and a strategic roadmap to improve revenue and customer targeting.

Project Objectives

Perform structured end-to-end data analysis

Identify variables influencing Total Sales

Analyze product and regional sales performance

Segment customers based on spending behavior

Develop actionable business recommendations

Deliver a portfolio-ready analytics project

Dataset Description

Initial Dataset:

100 rows

7 columns

Expanded Dataset:

1000+ rows (to meet technical requirement of minimum 500 rows)

Features Included:

Date

Product

Quantity

Price

Customer_ID

Region

Total_Sales

Engineered Features:

Month (derived from Date)

Profit (assumed 20% margin of Total_Sales)

Final dataset used for analysis: cleaned_data.csv

Repository Structure
retail_sales_capstone/
│
├── README.md
├── capstone_analysis.ipynb
└── data/
    ├── raw_data.csv
    └── cleaned_data.csv

Setup and Installation
Requirements

Python 3.10+

VS Code or Jupyter Notebook

Required Libraries

Install using:

pip install pandas numpy matplotlib seaborn scikit-learn

How to Run

Clone the repository

Open capstone_analysis.ipynb

Run all cells sequentially

Review outputs and visualizations

Project Workflow
Data Cleaning Phase

Load raw dataset

Expand dataset to exceed 1000 rows

Convert Date to datetime format

Create Month feature

Create Profit feature

Remove duplicates

Save cleaned dataset

Exploratory Data Analysis (EDA)

Visualizations created:

Monthly Sales Trend (Line Chart)

Sales by Region (Bar Chart)

Sales by Product (Bar Chart)

Quantity vs Total Sales (Scatter Plot)

Correlation Heatmap

Profit by Region

Advanced Analysis
Correlation Analysis

Identified strong relationships between Quantity, Price, Total_Sales, and Profit.

Linear Regression Model

Modeled Total_Sales as a function of Quantity and Price.

Key Insight:

Quantity has significantly stronger impact on revenue compared to Price.

Revenue growth is primarily volume-driven.

Customer Segmentation (K-Means Clustering)

Cluster 0: Low-value customers

Cluster 1: Medium-value customers

Cluster 2: High-value customers

High-value customers contribute disproportionately to total revenue.

Key Business Insights

Revenue is strongly influenced by purchase volume.

Regional sales performance varies significantly.

Customer base naturally segments into distinct spending groups.

Profit scales proportionally with total sales.

Strategic Recommendations

Increase average order quantity through bundling and upselling.

Implement loyalty program targeting high-value customers.

Optimize marketing allocation by region.

Improve inventory planning for top-performing products.

Introduce predictive demand forecasting models.

Implementation Roadmap

Phase 1 (0–3 Months):

Launch upselling campaigns

Identify high-value customers

Phase 2 (3–6 Months):

Deploy loyalty program

Optimize regional marketing

Phase 3 (6–12 Months):

Implement predictive analytics for pricing and inventory

Technical Requirements Fulfillment

Dataset size exceeds 500 rows

Applied at least 3 analysis techniques:

Correlation Analysis

Linear Regression

K-Means Clustering

Created more than 5 professional visualizations

Complete documentation included

Business implementation plan developed

Tools Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

VS Code

Expected Business Impact

10–15% potential revenue growth

Improved customer retention

Optimized marketing spend

Data-driven strategic decision-making

Conclusion

This capstone demonstrates a structured real-world analytics workflow from raw data processing to executive-level strategic recommendations. The project highlights how statistical modeling and machine learning techniques can be leveraged to drive measurable business outcomes.
