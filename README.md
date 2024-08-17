# Contoso-Sales-PowerBI
Welcome to my PowerBI Showcase GitHub repository! Here, you'll find an interacive dashboard, insightful report, and data visualizations demonstrating my expertise in PowerBI, a powerful business intelligence tool.

## [Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiOTkzZTI0MzAtMWFiNi00MjEzLWFhYTItMjIyZGNiMDljMGZkIiwidCI6ImE4ZWVjMjgxLWFhYTMtNGRhZS1hYzliLTlhMzk4YjkyMTVlNyIsImMiOjN9)

## Table of Contents

- [Introduction](#introduction)
- [Dataset Source](#dataset-source)
- [Dataset Contents and Structure](#dataset-contents-and-structure)
- [Dashboard Insights](#dashboard-insights)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Recommendations](#recommendations)
- [Features](#features)
- [License](#license)

## Introduction
This repository offers a Power BI dashboard designed to analyze sales data from the Contoso Inc. The dashboard gives insights into key sales indicators, to understand the key factors, and allows users to interact with the data using various features.


## Dataset Source
The dataset used for this dashboard is **"ContosoSalesForPowerBI"**, which includes over two million rows of sales data. The dataset can be downloaded from the following link:

- [Contoso Sales Data for Power BI](https://www.microsoft.com/en-us/download/details.aspx?id=46801)

## Dataset Contents and Structure
The Contoso sales data consists over 2.28 millions rows, providing a robust datasets that captures extensive sales transactions. This will allow me to perform comprehensive analysis across various dimensions including time, product categories, and sales channels and ensuring the insights derived are statistically significant and reflective in business trends.

![Dashboard Screenshot](./Dashboard%20Image/Data%20Model.png)


#### Analyze Contoso's sales data to understand key trends and identify opportunities for growth.
Requirement Gathering:
The following are our stakeholders: Sales, Marketing, Product & Operations

### To understand more about data and the context, we need to ask the following questions:
1. How are sales performing year over year (YoY)?
2. What impact do discounts have on sales ?
3. Which Product categories are driving revenues?
4. How the different sales channels are performing in the each years? 


The questions will help us to understand the business nature steps to analyse the categories, identifying the KPI

**North Star KPI:** Net sales after discounts.

**Secondary Metrics:** Gross Sales, Total Discount Amount, Sales by channel and class.

## Dashboard Insights
The dashboard provides comprehensive insights into Contoso's sales performance, by emphasizing important aspects including net and gross sales, yearly sales trends, sales distribution by class and channel, discount trends, and significant variables influencing unit prices. With the use of these capabilities, stakeholders may manage discounts wisely, enhance pricing tactics, and maximize sales strategies by making data-driven decisions.

In preparation for analysis a rigorous assessment of data quality was undertaken to ascertain and address potential issues.

Data Cleaning: Changing any non relevant data, adding new columns or converting into datatime format, creating helper columns, fixing typo in naming convention, maintaining data consistency and removing redundancy.



![Dashboard Screenshot](./Dashboard%20Image/sales.png)

![](./Dashboard%20Image/keyinfluencer.png)


## Key Performance Indicators (KPIs)
The dashboard features several KPIs to aid in the analysis:

1. **Gross Sales**: Shows the total gross sales amount.
   - ***Importance***: Provides a measure of overall revenue before any discounts are applied.

2. **Net Sales**: Displays the total net sales amount after discounts
    - ***Importance***: Reflects the actual revenue earned after discounts, crucial for profitability analysis.

3. **Total Discount Amount**: Displays the total discount amount given across all sales.
    - ***Importance***: Provides a quick reference to the overall discount impact on sales.

4. **Sales by Class**: Categorizes sales by class (Regular, Deluxe, Economy).
    - ***Importance***: Highlights customer preferences and helps in understanding the contribution of each class to total sales.

5. **Sales by Channel**: Breaks down sales by different channels (store, internet, reseller, catalog).
    - ***Importance***: Identifies the performance of various sales channels, aiding in strategic decision-making.

## Features
The dashboard highlights several key features:
- **Gross and Net Sales Overview**: 
    - ***Gross Sales***: Visualize the total gross sales amounting to $8.3412 billion.
    - ***Net Sales***: Display the total net sales, which come to $8.1174 billion, to understand the impact of discounts on sales.

- **Yearly Sales Performance**:
    - ***Trend Analysis***: Examine the sales amount, net sales, and discount amount from 2011 to 2013, showcasing the peak sales year and subsequent decline.
    - ***Bar Chart Visualization***: Utilize bar charts to represent the annual sales performance.

- **Sales by Channel**:
    - ***Channel Distribution***: Use a donut chart to show the distribution of sales across different channels-store, internet, reseller, and catalog.
    - ***Key Insight***: Identify the significance of store and online channels in Contoso's sales strategy.

- **Sales by Class**:
    - ***Class Categorization***: Categorize sales by class names (Regular, Deluxe, Economy) in a horizontal bar chart.
    ***Customer Preference***: Highlight that the Regular class contributes the highest sales, indicating customer preference.

- **Monthly Discount Amount**:
    - ***Discount Trends***: Display monthly discount amounts using a line graph to identify peak discount periods and seasonal trends.

- **Product Category and Subcategory Performance**:
    - ***Revenue Analysis***: Highlight high-revenue categories such as computers, cameras, and televisions using a tree map.
    ***Strategic Focus***: Determine which product lines generate the highest revenues and require strategic attention.


## Recommendations
Based on the comprehensive analysis conducted, the following recommendations are proposed for consideration by the appropriate cross-functional teams.

### Sales and Marketing
- Leverage the most effective sales channels and allocate resources to peak periods.

- Tailor the campaigns to support top-selling products

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for more details.