# Bike Sales-Analysis

## Table Of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Limitations](#limitations)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Data Manipulation](#data-manipulation)
- [Summary Of Findings](#summary-of-findings)
- [Results and Findings](#results-and-findings)
- [Conclusion and Recommendation](#conclusion-and-recommendation)



### Project Overview
---
This data analysis project aims to give an accurate insight into the regional sales of a bike company in the United States of America, the company wants to know which states/regions have purchased more bikes over the years.
This project seeks to analyse every aspect of the data from purchases to orders so as to identify trends and patterns to draw a valid conclusion and make reasonable decisions from recommendations based on the findings.

![PowerBI](https://github.com/quhduzski/Sales-Analysis/assets/89488315/a198aaf6-d1d4-4cde-a563-75766f12906a)

### Data Source
---
The data used to carry out the analysis of this project was derived from a secondary source (online) "Sale-Analysis.csv" with detailed information on the company's sales from region to region within various years.

### Limitations
---

The limitations of this analysis include a restricted dataset, the absence of causal relationships, potential shifts in market dynamics, a focus on specific products and regions, lack of contextual information, dependence on data quality, and generalization based on historical trends.

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

### Exploratory Data Analysis
---
1. What country has the highest sales and order
2. Which State have the highest bike purchase
3. Which region generates more revenue and why
4. Which product has the highest revenue generated
5. what year/period did sales peak?

### Data Analysis
---
Analysis was carried out using SQL
```
Select * from Sales where year in (2011, 2013, 2015) > 100
```

### Data Manipulation
---
The data was manipulated in PowerQuery before being used for report generation. It was used to get the total sum of sales and orders from all the states and regions using the base measurement and also some columns were manipulated.

### Summary Of Findings
---

This data analysis project focuses on evaluating the regional sales of a bike company in the United States. The objective is to identify states and regions with higher bike purchases, analyze various data aspects, and draw meaningful conclusions for informed decision-making. The findings include total sales revenue of $85 million and 1 million orders over the years. California leads in both quantity ordered (267,614) and revenue generated (around $17 million). The road-150 product contributes the most revenue, while the year 2015 stands out with the highest revenue of $20 million.


### Results And Findings
---
The findings from the analysis are as follows:

1. We found that the Total revenue for Sales over the years is 85 million while the order is 1 million
2. Based on quantity ordered by the state, California has the highest order with 267,614 while the USA has the highest order among the countries.
3. Based on revenue generated, California has the highest revenue of around 17 million while the USA has the highest revenue among the countries.
4. The bike product with the most revenue is the road-150, while the product with the most quantity ordered is the water bottle -30 oz.
5. 2015 was the year with the most revenue generated with 20 million revenue.


### Conclusion and Recommendation
---

In conclusion, the data analysis reveals that the bike company has accumulated a total revenue of $85 million from 1 million orders over the years. California emerges as a significant contributor, leading both in quantity ordered (267,614) and revenue generated (around $17 million). The road-150 bike product stands out as the top revenue-generating item, while the water bottle -30 oz. is the most frequently ordered product. Notably, the year 2015 marks a peak in revenue, reaching $20 million.

#### Recommendations:
---
1. Focus on California: Given its substantial contribution to both order quantity and revenue, it is advisable to prioritize marketing and sales efforts in California to further capitalize on the strong market presence.
2. Product Emphasis: Since the road-150 product is the top revenue generator, consider implementing targeted marketing strategies or promotions to enhance its sales further. Additionally, monitor the demand for the water bottle -30 oz. and explore opportunities for increased sales.
3. Yearly Analysis: Regularly conduct yearly analyses to track trends and identify potential peak periods. Understanding the factors contributing to the revenue peak in 2015 can aid in formulating strategies for future growth.
4. Expand Market Presence: While California is a key market, explore opportunities to expand the company's presence in other high-potential states or regions, especially those with increasing order quantities and revenue potential.

By implementing these recommendations, the company can leverage its strengths, address specific product demands, and strategically expand its market reach for sustained growth.



