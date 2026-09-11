# Supermarket Sales Analysis

## Project Overview

This project analyzes 1,000 supermarket sales transactions to identify sales trends, customer behavior, product performance, payment preferences, and branch performance.

Python and Pandas were used for data preparation and exploratory data analysis, Matplotlib was used for data visualization, and Power BI was used to create an interactive dashboard.

## Problem Statement

The objective is to analyze supermarket transaction data and identify important business patterns that can support better sales and marketing decisions.

## Dataset

The Supermarket Sales Dataset contains 1,000 transaction records and 17 original columns.

The dataset includes:
- Branch and city
- Customer type
- Gender
- Product line
- Unit price
- Quantity
- Total sales
- Payment method
- Gross income
- Customer rating
- Date and time

## Data Preparation

The dataset was checked for:
- Missing values
- Duplicate records
- Invalid numerical values
- Date and time formats

No missing values or duplicate records were found. No invalid numerical values were identified.

The Date column was converted to datetime format, and additional features including Year, Month, Month Name, Day, Day Name, and Hour were created.

## Exploratory Data Analysis

The analysis examined:
- Descriptive statistics
- Product-line performance
- Branch performance
- Monthly sales trends
- Customer type performance
- Payment method performance
- Correlations between numerical variables
- Outliers

## Data Visualizations

Five visualizations were created:
1. Total Sales by Branch
2. Total Sales by Product Line
3. Monthly Sales Trend
4. Total Sales by Payment Method
5. Quantity Sold by Product Line

## Power BI Dashboard

An interactive Power BI dashboard was created with:
- Total Sales KPI
- Gross Income KPI
- Quantity Sold KPI
- Average Customer Rating KPI
- Branch sales visualization
- Product-line sales visualization
- Monthly sales trend
- Payment method visualization
- Branch slicer
- Customer Type slicer
- Product Line slicer

## Key Business Insights

- Branch C recorded the highest total sales.
- Food and beverages was the strongest product line by sales.
- Health and beauty recorded the lowest product-line sales.
- January had the highest monthly sales, while February had the lowest.
- Member customers generated slightly higher sales than Normal customers.
- Cash generated the highest sales among the payment methods.
- Quantity and unit price showed positive relationships with total sales.
- Customer rating had very little relationship with total sales.

## Recommendations

1. Improve the performance of lower-selling product lines through targeted promotions, discounts, and improved product placement.
2. Strengthen the membership program through loyalty rewards and member-exclusive offers.
3. Investigate the February sales decline and introduce targeted campaigns during weaker sales periods.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI
- Git
- GitHub

## Conclusion

The analysis provides a clear view of supermarket sales performance and customer behavior. The findings can help management improve product performance, strengthen customer loyalty, and address periods of weaker sales.