Project Overview

This project analyses more than twenty five thousand Amazon clothing sales records. The objective was to understand sales patterns, discount behaviour, return trends, delivery performance, and customer demographics. The analysis was conducted entirely in Microsoft Excel using formulas, pivot tables, charts, conditional formatting, and an interactive dashboard. The project demonstrates end to end data cleaning, transformation, hypothesis testing, and business oriented insight generation.

Dataset Description

The dataset contains more than twenty five thousand sales entries from Amazon’s clothing category. Each row represents a unique order. The data covers product information, pricing, discount percentage, customer details, payment method, device type, review ratings, and delivery performance.

Main columns include:
order_id
customer_id
product_id
product_name
main_category
sub_category
brand
price
quantity
discount_percent
final_price
payment_method
review_rating
order_date
delivery_days
region
customer_age_group
device_type

Project Workflow

The project followed a structured workflow in Excel.

Data Cleaning and Preparation
Converted order_date to proper date format.
Corrected data types for price, discount, quantity, and rating.
Identified and resolved missing values using mean, median or mode according to the column type.
Removed duplicates and validated numeric columns.
Verified that final_price followed the expected formula structure.

Data Transformation
Created new calculated columns:
Discount Amount
Unit Price
Order Month
Order Year
Order Weekday
Delivery Speed Flag (Fast, Medium, Slow)

Built category level and customer level summaries using multiple pivot tables.

Data Analysis
Performed univariate and bivariate analysis.
Used pivot charts to examine relationships between discounts, returns, ratings, sales, regions and age groups.
Explored brand performance and product category performance.
Examined delivery speed patterns and device usage trends.
Added slicers for category, region and age group.

Dashboard Development
Created an interactive Excel dashboard that includes:
Revenue trends
Top selling categories and brands
Return hotspots
Customer segmentation overview
Delivery speed distribution
Device and payment behaviour

Key Insights

Women’s clothing contributed the highest share of sales with more consistent monthly revenue compared with other categories.
Orders placed through mobile devices dominated and made up most sales across age groups.
Regions in the southern United States produced higher revenue than other regions.
Higher discount percentages increased quantity sold but also showed a rise in return likelihood.
Delivery delays beyond five days were linked to lower review ratings.
Younger age groups gave lower ratings compared with older customers.
Premium brands such as Nike and Zara generated higher revenue despite offering fewer discounts.
Fast deliveries (zero to two days) were the most common delivery type across the dataset.

Final Deliverables

Cleaned Excel dataset.
Excel analysis sheets with pivot tables and charts.
Interactive Excel dashboard.
PDF report summarising insights and graphs.
