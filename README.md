# Contoso-Sales-PowerBI
Welcome to my PowerBI Showcase GitHub repository! Here, you'll find an interacive dashboard, insightful report, and data visualizations demonstrating my expertise in PowerBI, a powerful business intelligence tool.

## [Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiOTkzZTI0MzAtMWFiNi00MjEzLWFhYTItMjIyZGNiMDljMGZkIiwidCI6ImE4ZWVjMjgxLWFhYTMtNGRhZS1hYzliLTlhMzk4YjkyMTVlNyIsImMiOjN9)

## Table of Contents

- [Introduction](#introduction)
- [Dataset Source](#dataset-source)
- [Dataset Contents and Structure](#dataset-contents-and-structure)
- [Dashboard Insights](#dashboard-insights)
- [Sales Overview](#sales-overview)
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

![Data Model](./Dashboard%20Image/Data%20Model.png)


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


## Sales Overview

### By Time Period
![Sales Overview](./Dashboard%20Image/sales.png)
- Between 2011 and 2013, Contoso's total sales amounted to $8.3412 billion in gross sales and $8.1174 billion in net sales, highlighting the impact of discounts on revenue. The peak sales year was 2011, with $3.14 billion in sales, followed by a gradual decline in the subsequent years, which coincided with a notable reduction in discounting. 

### Sales by Channel
- The distribution of sales across different channels is prominently displayed, showing that the store channel was the leader with 58.18% of total sales. This was followed by internet sales at 20.25%, reseller at 13.25%, and catalog sales at 8.32%. These insights highlight the critical importance of in-store and online sales channels to Contoso's overall strategy.

### Sales by Product Class
- Sales were broken down by product class, revealing that the Regular class dominated with $5.18 billion in sales, followed by the Deluxe class at $1.96 billion, and the Economy class at $1.21 billion. This distribution indicates a strong customer preference for Regular class products, which is vital information for inventory management and marketing strategies.

## By Product and Key Influencer
![](./Dashboard%20Image/keyinfluencer.png)

### Discount Trends
- Monthly discount trends were tracked to identify peak discount periods and seasonal tendencies. This data is crucial for optimizing discount strategies and ensuring that they align with broader business objectives.

### Product and Regional Performance
- A detailed treemap highlighted the performance of various product categories and subcategories, aiding in the identification of high-revenue areas that should be prioritized. Additionally, the regional sales distribution was analyzed, showing where the majority of sales occurred, which is essential for formulating regional market strategies.

### Key Influencers
- The dashboard also provided insights into key influencers of unit pricing, product category performance, and discount patterns. High-revenue categories like computers, cameras, and televisions were identified as critical areas that require strategic attention to maximize profitability. The influence of brand names, manufacturers, and product categories on unit price reductions was also analyzed, helping to refine pricing strategies and competitive positioning.

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
- **Investigate YoY Sales Decline:** Conduct a deeper analysis to understand the underlying factors contributing to the significant YoY drop in sales from 2012 to 2013, beyond the easing of discounting strategies.
- **Focus Marketing Efforts:** Increase marketing focus on high-performing product categories like Computers, Cameras, and Televisions. Consider reallocating budget from underperforming channels to more effective ones, like online sales and stores.
- **Enhance Customer Loyalty:** Collaborate with the operations team to improve customer experience by reducing delivery times, especially for high-value customers.

### Product and Inventory
- Tailor the campaigns to support top-selling products.
- Optimize inventory levels based on seasonal demand forecasts to reduce overstock or stockouts.
- **Address High Refund Rates:** Explore the reasons behind high refund rates in certain products and improve quality or customer support for these items to reduce dissatisfaction and returns.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for more details.