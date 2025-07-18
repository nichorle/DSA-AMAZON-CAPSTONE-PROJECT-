# DSA DOCUMENTATION

This is a portfolio of how I started  building  my DSA Data Analysis with Incubator Hub.

It has been a wondeful journey of learning from Excel, SQL and Power BI and i wish to continue the learning process.


### PROJECT TOPIC: AMAZON CAPSTON PROJECT

#### Amazon-Product-overview-Analysis
Portfolio for my DSA Data Analysis Capstone Project with Incubator Hub. A comprehensive Excel-based analytics project on Amazon product reviews, pricing, and discount trends, developed during my time at DSA Incubator. The project utilized pivot tables, slicers, calculated fields, and interactive dashboards to uncover actionable insights on product performance, category trends, customer behavior, and revenue opportunities.

## PROJECT INFORMATION
 
Organisation: RetailTech Insights
 
Sector: E-commerce Analytics

Analyst Role: Junior Data Analyst

Analysis Tools Used: Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Slicers)

## DATASET DESCRIPTION
•	Total Records: 1,465

•	Columns: 16

•	Source: Web-scraped Amazon product review data
•	Each row represents: A unique product details
•	**The column Fields pertinent to the analysis included:**

        o	Product name
        
        o	Product Category
        
        o	Actual price & Discounted price
        
        o	Discount Percentage %
        
        o	Rating   
        
        o	Review content (aggregated in some columns)
        
        o	Revenue potential fields (derived)
        
## ANALYSIS TASKS AND SOLUTION
|Nos| Task | Solution/ Tools used|
|---|-------|----------------------|
|1| What is the average discount percentage by product category| Pivot Table, Average formula
|2| How many products are listed under each category?|	Pivot Table + Count of product name
|3|	What is the total number of reviews per category?|	Pivot + Count of Review
|4| Which products have the highest average ratings?|	Sorting based on calculated Average Rating on pivot table
|5|	What is the actual vs discounted price by category?|	Grouped Bar Chart + Pivot Summary
|6|	Which products have the highest number of reviews?|	Top-# Analysis using Sorting + Pivot Table
|7|	How many products have ≥ 50% discount?|	Filter High Discount column
|8|	What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?|	Line chart with Pivot Count
|9|	Total potential revenue (actual_price × rating_count) per category?|	New Calculated Column on Power query + Pivot Table SUM
|10| Unique product count per price range bucket (<₹200, ₹200–₹500, >₹500)?| Added conditional column in Power query + Donut Chart
|11| Relationship between rating and discount level?|	Pivot Table +Column Chart
|12| How many products have fewer than 1,000 reviews?|	Added Conditional Column + Column Chart
|13| Categories with highest average discount?|	Sorted Pivot Table by Discount%
|14| Top 5 products by combined review count and rating| Pivot, Sum of rating, Count of reviews.

## Analysed File

https://github.com/nichorle/DSA-AMAZON-CAPSTONE-PROJECT-/commit/29a36b5be123346919d9f10df91c610f2167e0f0

## Visual Dashboard
https://github.com/nichorle/DSA-AMAZON-CAPSTONE-PROJECT-/commit/a0e5385ffa047d0924a5c4f6e99915cf29d30bf5


