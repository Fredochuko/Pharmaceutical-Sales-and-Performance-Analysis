## Pharmaceutical Sales and Performance Analysis Using Microsoft Excel
## Project Overview
Pharmaceutical companies generate, process, and store large volumes of data across departments, such as sales, research and development, quality control and assurance. However, raw data storage alone is not enough to provide actionable insights for making key business decision.
This project focuses on analyzing the sales of pharmaceuticals products. The analysis was carried out using Microsoft Excel to gain insights into patterns in product demand, regional sales performance, and revenues generation.
The raw data obtained and stored were transformed into structured insights through data cleaning, formulas, pivot table analysis and visual representation. The information from this analysis provides management with the needed support for strategic planning, product optimization, revenue drivers, and sales performance improvement.
## Business Summary
This project analyzes pharmaceutical sales data to evaluate product performance, regional revenue contribution, and yearly sales trends using Microsoft Excel. The analysis identified key revenue-generating products, highlighted Poland as the strongest-performing market, and revealed consistent growth in sales over time. The insights provide data-driven recommendations to support strategic decision-making, product optimization, and sales performance improvement.
## Executive Dashboard Preview
 <img width="613" height="305" alt="Pharmaceutical_Sales_Analysis_Dashboard" src="https://github.com/user-attachments/assets/12712002-e3e6-4641-bb6d-4d119edc96fb" />

## Skills Demonstrated
1.	Data cleaning and transformation
2.	Pivot table analysis
3.	Data Visualization
4.	Dashboard storytelling
5.	Business Analysis and strategic recommendation
6.	KPI calculation 
7.	Analytical thinking and problem-solving
## Tools Used
1.	Microsoft Excel 
2.	Power Query 
3.	PivotTables 
4.	Excel Formulas and Functions 
5.	Data Visualization Techniques
## Business Problem
The pharmaceutical company records and stores large volumes of transactional sales data daily, however without proper analysis it difficult to gain insights on:
1.	Which products generate the highest total sales?
2.	Which country performs best in terms of sales? 
3.	How sales performance change over time (yearly sales trend)? 
4.	What are the top and bottom performing products? 
5.	What is the total sales value across the dataset? 
## Business Objectives
The objectives of this project analysis are:
1.	Clean and prepare the pharmaceutical products.
2.	Identify the top performing pharmaceutical products.
3.	Determine the country generating the highest sales revenue.
4.	Analyze the yearly sales performance trend.
5.	Identify top and bottom performing products.
6.	Calculate the total sales revenue generated.
7.	Present findings in a structured analytical report for management decision-making.
## Dataset Description
The dataset consists of 336 pharmaceuticals sales product records collected between 2017 and 2018, and includes fields such as Distributors, Customer Name, Product Name, Price, Quantity, Country, Channel, Sales Representative etc. which support sales and product analysis. 
## Data Cleaning Process
Data cleaning was done using power query to ensure accuracy and consistency before analysis.
## Remove Duplicate 
The fields and records were checked to ensure there was no duplicate values using power query to avoid double counting in sales calculations.
## Handling Missing Value
The filter function was used to identify blank cells and missing values were handled appropriately such as recalculating missing column values for the sales columns.
## Data Types
The fields and were checked to ensure they were properly formatted. Where there was an improperly formatted fields, the appropriate data type was used as replacement to ensure a clean and accurate data analysis process. E.g numeric fields to number format and date field to date datatype format.
## Text Format
Inconsistencies in text such as capitalization differences were put in order to eliminate grouping errors and text entries were standardized in power query using the transform function and clicking on the appropriate format style (uppercase, lowercase, capitalized each word etc).
## Analytical Conditional Columns
1.	Gross sales column was created in power query editor to calculates and ensure accurate total sales values. This column takes into consideration all the positive values in the cell’s column ignoring the negatives. This was gotten by using the formula “=IF (Sales > 0, Sales, 0)” in power query editor.
2.	A return or negative sales column was created to handle the negative sales values. This helps to gain insight on any product sold that was return. This was gotten using the formula “=IF (Sales < 0, Sales, 0)’ in the power query editor.
## Data Analysis
The pharmaceuticals sales and performance analysis were conducted using Microsoft Excel formulas, Power Query Editor, and PivotTables.
## Key Calculations and Formulas
```
1.	Total Sales / Total Revenue: the total sales across the dataset were calculated using the gross sales columns and this column takes into consideration all positive sales or finished transactions. The formula for calculating the total sales is, “=SUM (Gross Sales Column)”.
2.	Average Product Price: this shows the average price for each product. This measure is a key metric to understanding pricing strategy and revenue performance. The is gotten using “=AVERAGE (Price Column).
3.	Total Net Revenue: this was calculated using the sales column and it is the total revenue generated after deducting all cost and expenses. The sales column was used in calculating as it had the return values (negative sales). The formula used “=SUM (Sales column).
4.	Total Return: shows product returns or refunds. It gives the total value of pharmaceuticals products that were return due to defects, wrong orders etc. it was calculated using “=SUM (Returned column).
5.	Total Units Sold: this is the sum of all units of pharmaceutical products that were sold across the dataset. It was gotten by “=SUM (Quantity column).
6.	Number of Products: this refers to the total count of unique pharmaceuticals products that were sold. It was gotten by using “DISTINCTCOUNT (Product Name).
```
## Pivot Table Analysis

## 1.  Top 5 Product Performance

<img width="247" height="170" alt="Pivot_Top_5_Product_Performance" src="https://github.com/user-attachments/assets/71374d6a-cb45-4a79-acb4-94542bed8a80" />

This pivot table ranks pharmaceutical products based on total sales revenue, allowing quick identification of the company’s highest-performing products.

## 2.  Country Sales Performance

<img width="204" height="124" alt="Pivot_Country_Sales_Performance" src="https://github.com/user-attachments/assets/10589715-e5fe-46b9-9e49-494d27bb2ad4" />

This pivot table summarizes total pharmaceutical sales revenue by country, enabling comparison of regional market performance. The analysis reveals that Poland generated the highest total sales revenue, significantly outperforming Germany.

## 3.  Yearly Sales Trend

<img width="205" height="127" alt="Pivot_Yearly_Sales_Trend" src="https://github.com/user-attachments/assets/42e7b84d-4a29-4f9a-9ccc-01c64c16bdee" />

This pivot table analyzes pharmaceutical sales performance over time by aggregating total sales revenue by year. It reveals how revenue changes across reporting periods and helps identify growth patterns or potential declines.

## 4.  Returned Products

<img width="287" height="118" alt="Pivot_Products_Returned" src="https://github.com/user-attachments/assets/c537fe21-1066-4afb-8e1e-15ba2562a8f1" />

This pivot table evaluates product returns by summarizing negative sales values recorded in the dataset. Returns represent refunded or reversed transactions and provide insight into operational or product-related issues.

## Key Insights and Findings
## Product Performance
Total sales revenue generated across all markets was $1,748,904 with some pharmaceutical products contributing significantly more revenue than others, indicating strong product demand and market acceptance. Ribabylor, an antiseptic was the highest sold pharmaceutical products generating a revenue of $240,597 in sales. On the other hand, Raparidol (a mood stabilizer) and Immurenol Tamarate (an antipyretic) had zero sales. 
Raparidol and immurenol Tamarate also had a negative sale, an indication of return which may be due to product defect, expiration or distribution inefficiencies. From the analysis, it shows that high-performing products represent the core revenue drivers for the company, while low performing products contribute minimal revenue and may require marketing support or product review.
## Regional Performance
Sales distribution across the two countries reveals that the Poland pharmaceutical markets ($1,140,558) outperform the German pharmaceutical markets ($608,346) in terms of sales or revenue generated. The Poland markets may benefit from stronger distribution networks, higher product demand and better sales team performance.
## Sales Trend Over Time
Yearly sales analysis highlights whether the company is experiencing consistent revenue growth, seasonal fluctuations or declining product demands.
Understanding these patterns helps guide forecasting and strategic planning. The analysis shows a straight-line graph an indicative of a positive progressive revenue generation over the years. Pharmaceuticals sales increased steadily from 2017 to 2018, revealing consistent market penetration and expansion.
## Product Portfolio Insights
Identifying bottom-performing products can help management reconsider product positioning, improve marketing, and discontinue underperforming drugs
## Business Recommendations
1.	Products with zero or negative sales should be evaluated for pricing issues, product relevance, distribution challenges, or potential discontinuation.
2.	Poland generated more revenue in comparison to Germany. Successful regional sales strategies from Poland region can be replicated and implemented in the lower performing regions of Germany.
3.	The positive yearly sales trend can be leverage for demand forecasting, inventory planning, and long-term strategic decision-making.
4.	Invest more in high performing products by increasing marketing effort, inventory availability and distribution support for top-selling products such Ribabylor, an antiseptic to maximize revenue growth.
5.	Negative sales or returned products should be investigated and the root cause addressed as this could reduce revenue loss and improve customer satisfaction.
## Business Impacts
1.	The overall profitability of pharmaceutical sales can be optimized by focusing more on high-demand products.
2.	Identifying and resolving the causes of product returns can reduce financial losses and increase revenue generation.
3.	Successful application of regional strategies like efficient product distribution can improve low performing market, hence creating an avenue for market expansion.
4.	The sales performance trend provides data-driven insight for better forecasting which supports efficient production, inventory, and supply chain planning.
5.	The analysis enable management to rely on data-driven insights rather than assumptions, hence improving decision-making.
## Dashboard Features / Functionality
The dashboard was designed as a centralized operational monitoring tool featuring:
1.	KPI summary cards.
2.	Country sales performance.
3.	Best/Worst pharmaceutical products performance charts.
4.	Yearly sales trend.
5.	Product class sales.
6.	Product returned.
## Conclusion
This project transformed raw pharmaceutical sales data into meaningful business insights through data cleaning, structured analysis, and visualization using Microsoft Excel. The analysis identified key revenue-driving products, evaluated regional sales performance, and revealed a positive yearly sales trend, providing a clearer understanding of overall business performance.
The findings demonstrate how data analysis can support strategic decision-making by helping management optimize product portfolios, improve market focus, and enhance sales operations. Overall, this project highlights the value of leveraging data-driven insights to improve efficiency, profitability, and long-term business growth.
## How to Reproduce this Project
1.	Download the dataset from the /data folder.
2.	Open the .xlsx file in Microsoft Excel.
3.	Interact with slicers and filters.


## Author
Disi, Ogheneochuko Fredrick

Data Analyst | Business Intelligence Enthusiast


