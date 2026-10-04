Nassau Candy Distributor — Sales & Profitability Analysis
An end-to-end Power BI business intelligence project analyzing sales, costs, profitability, product performance, division performance, regional trends, and profit concentration for Nassau Candy Distributor.
The project transforms raw transaction-level sales data into an interactive 6-page Power BI dashboard designed to help management identify profitable products, margin risks, growth opportunities, and areas requiring cost optimization.

Project Overview

Nassau Candy Distributor is analyzed across multiple dimensions including:
Products
Divisions
Regions
Factories
Order dates
Sales
Costs
Units
Gross profit
Gross margin
The primary objective was to answer:
Which products, divisions, regions, and factories are driving sales and profitability, and where are the biggest business opportunities or risks?

Dataset

The cleaned dataset contains:
Metric
Value
Transactions
10,194+
Products
15
Divisions
3
Regions
4
Factories
5
Analysis Period
2024–2025

Divisions

Chocolate
Other
Sugar
Regions
Atlantic
Gulf
Interior
Pacific

Business KPIs

The overall dataset produced the following results:
KPI
Result
Total Sales
$141,783.63
Total Cost
$48,340.83
Gross Profit
$93,442.80
Gross Margin
65.91%
Units Sold
38,654
Orders
8,549
Customers
5,044
Products
15


Tools & Technologies

Data Preparation
Power Query
Microsoft Excel / CSV
Data Visualization
Microsoft Power BI
Data Analysis
DAX
Power Query transformations
Data modeling
KPI analysis
Pareto analysis
Trend analysis
Dashboard Design
Interactive slicers
KPI cards
Bar charts
Line charts
Combo charts
Scatter plots
Tables
Pareto analysis

Data Cleaning & Transformation

The raw dataset was prepared using Power Query before building the dashboard.
Key data preparation steps
Removed duplicate records where applicable.
Handled missing and inconsistent values.
Standardized column data types.
Converted date fields into appropriate date formats.
Validated numeric fields such as Sales, Cost, Units, and Gross Profit.
Checked categorical fields including Product, Division, Region, and Factory.
Created a clean analysis-ready dataset.
Validated totals after transformation against the source data.
This ensured that the Power BI calculations were based on consistent and reliable data.

Dashboard Structure
The project contains 6 analytical pages.

1. Executive Overview
Objective
Provide a high-level view of overall business performance.
Key Components
Total Sales
Gross Profit
Gross Margin %
Units Sold
Profit per Unit
Sales vs Gross Profit trend
Division performance
Top 5 products
Profit contribution by division
Interactive date, division, and region filters
Business Question
How is the overall business performing?

2. Product Profitability
Objective
Analyze profitability at the individual product level.
Key Components
Total Products
Total Sales
Gross Profit
Average Product Margin
Profit per Unit
Top products by Gross Profit
Products by Gross Margin
Sales vs Margin scatter analysis
Product performance comparison
Business Questions
Which products generate the most profit?
Which products have the highest margins?
Which products have high sales but relatively low margins?
Which products represent potential growth opportunities?

3. Division Performance
Objective
Compare the performance of the three major business divisions.
Divisions
Chocolate
Other
Sugar
Key Components
Division-level Sales
Gross Profit
Gross Margin
Units Sold
Profit per Unit
Product Count
Revenue vs Gross Profit comparison
Division profitability analysis
Business Questions
Which division contributes the most revenue?
Which division is most profitable?
Which division has the strongest margin?
Where should management focus growth efforts?

4. Cost & Margin Diagnostics
Objective
Identify cost-heavy products and profitability risks.
Key Components
Total Sales
Total Cost
Gross Profit
Gross Margin
Profit per Unit
Cost vs Sales scatter plot
Cost % analysis
Product margin analysis
Margin Risk classification
Product-level risk table
Margin Risk Logic
Products are classified using:
Margin Risk =
VAR Margin = [Gross Margin %]
RETURN
    SWITCH(
        TRUE(),
        Margin < 0.30, "Critical",
        Margin < 0.50, "High",
        Margin < 0.70, "Medium",
        "Low"
    )
Business Questions
Which products have weak margins?
Which products have excessive costs?
Which products require pricing or cost optimization?
Where are the biggest profitability risks?

5. Profit Concentration
Objective
Understand how dependent the business is on a small number of products.
This page uses Pareto analysis to analyze the concentration of:
Gross Profit
Revenue
Key Components
Product Profit Ranking
Cumulative Gross Profit
Cumulative Gross Profit %
Product Sales Ranking
Cumulative Sales
Cumulative Sales %
Top 5 Profit %
Top 5 Sales %
Pareto Analysis
Products are ranked based on profitability, followed by cumulative contribution.
This allows management to identify whether:
A small number of products generate a disproportionately large share of business results.
Business Insight
The analysis shows a high concentration of profitability among the leading Chocolate products.
This creates both:
A strength, because the company has strong core products.
A risk, because performance is highly dependent on a relatively small product group.

6. Product Deep Dive
Objective
Allow users to investigate an individual product in detail.
Users can select a product and dynamically analyze:
Sales
Gross Profit
Gross Margin
Units Sold
Profit per Unit
Monthly performance
Margin trends
Cost vs Sales position
Interactive Filters
Product
Order Date
Region
Business Question
What is happening with this specific product, and how does its performance change over time?

Key Business Insights

1. Strong overall profitability
The business generated approximately:
$141.78K in sales
and:
$93.44K in gross profit
with a:
65.91% gross margin.
This indicates strong gross-level profitability.

2. Chocolate dominates the business
Chocolate generated approximately:
$131.69K Sales
$88.82K Gross Profit
67.45% Gross Margin
Chocolate contributes the vast majority of overall sales and profit.

3. Profit is highly concentrated
The top-performing products contribute a very large proportion of total gross profit.
This indicates strong dependence on a small number of core products.

4. 2025 showed strong growth
Sales and gross profit increased significantly from 2024 to 2025 while maintaining a relatively stable gross margin.
This indicates that the business was able to grow without a major deterioration in gross profitability.

5. Pacific is the largest sales region
Pacific generated the highest regional sales, while regional margins remained relatively consistent.
This suggests that the major opportunity is more focused on revenue expansion than significant regional margin restructuring.

6. Factory profitability varies significantly
Some factories operate with significantly stronger margins than others.
This highlights opportunities for:
Cost optimization
Production efficiency
Procurement improvements
Product mix optimization

7. Low-margin products require attention
Products with very low gross margins can generate revenue while contributing relatively little profit.
These products should be reviewed for:
Pricing
Production cost
Procurement cost
Distribution cost
Portfolio relevance

Business Recommendations

Based on the analysis, the business can:
1. Protect high-performing products
Maintain sufficient inventory and distribution capacity for the products responsible for the majority of sales and profit.
2. Reduce profit concentration
Develop secondary products to reduce dependency on the top-performing products.
3. Optimize low-margin products
Review pricing and costs for products with significantly below-average margins.
4. Improve factory efficiency
Investigate differences in factory-level profitability and identify opportunities to reduce production costs.
5. Expand underperforming divisions
Evaluate opportunities to increase sales from the Other and Sugar divisions.
6. Target regional growth
Focus sales and distribution efforts on regions with lower revenue potential while maintaining current margin levels.
7. Monitor performance continuously
Use the Power BI dashboard to monitor:
Sales → Cost → Profit → Margin → Product Performance
on a regular basis.

Key Learning Outcomes

This project helped develop practical experience in:
Data cleaning and transformation using Power Query
Data modeling in Power BI
Writing DAX measures
Building interactive dashboards
KPI development
Profitability analysis
Product segmentation
Pareto analysis
Trend analysis
Business storytelling with data
Converting analytical findings into business recommendations

Project Outcome

The final Power BI solution converts transaction-level sales data into an interactive management dashboard that provides visibility into:
Revenue → Costs → Profitability → Products → Divisions → Regions → Factories → Business Risks → Growth Opportunities
The project demonstrates an end-to-end Business Intelligence workflow, from raw data preparation to interactive visualization and actionable business insights.

Project Type

Business Intelligence | Data Analytics | Sales & Profitability Analysis
Primary Tool
Microsoft Power BI

Skills Demonstrated
Power Query • DAX • Data Cleaning • Data Modeling • Data Visualization • KPI Analysis • Business Analysis • Dashboard Design • Pareto Analysis
