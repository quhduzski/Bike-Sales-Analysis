# Bike Sales-Analysis

### Project Overview
---
This data analysis project aims to give an accurate insight into the regional sales of a bike company in the United States of America, the company wants to know which states/regions have purchased more bikes over the years.
This project seeks to analyse every aspect of the data from purchases to orders so as to identify trends and patterns to draw a valid conclusion and make reasonable decisions from recommendations based on the findings.

### Data Source
---
The data used to carry out the analysis of this project was derived from a secondary source (online) "Sale-Analysis.csv" with detailed information of the company's sales from region to region within various years.

### Tools
---
The tools used for this project are stated below
- Excel: [Data Cleaning](https://support.microsoft.com/en-au/office/top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19)
- PowerQuery: [Data Manipulation](https://learn.microsoft.com/en-us/power-query/best-practices)
- SQL: [Data Analysis](https://www.udacity.com/course/sql-for-data-analysis--ud198)
- PowerBi: [Dashboard Report](https://learn.microsoft.com/en-us/power-bi/create-reports/service-dashboards)

###  Data Cleaning
---
- Loading and inspection of the data
- Handling missing values
- Data Cleaning, Formatting, and Analysing

### Exploratory Data Analysis (EDA)
---
1. What country has the highest sales and order
2. Which State have the highest bike purchase
3. Which region generates more revenue and why
4. Which state/region has the lowest sales and revenue generated
5. what year/period did sales peak?

### Data Analysis
Analysis was carried out using SQL
```
Select * from Sales where year in (2011, 2013, 2015) > 100
```

### Data Manipulation
The data was manipulated in PowerQuery before being used for report generation. It was used to get the total sum of sales and order from all the states and region using the base measurement and also some columns were manipulated.
