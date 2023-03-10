# Super Store Analysis

![](building-g55a88d54a_1920.jpg)
---
## Introduction
This is a power BI project on sales analysis of an imaginary store called **Super Stores**.
The project id to analyze and gain insights to answer important questions and help the store make data driven decisions.

**_Disclaimer_**: _All datasets and reports do not represent any company, store or organization. This is just a dummy dataset to demonstrate the capabilities of Power BI._

## Problem statement
1. How sales trended over the months and years.
2. Average sales by day of the week.
3. How customer segments rank over the months.
4. Top states by sales.
5. Bottom states by sales.
6. Sales distribution by city.
7. Key influencers.

To find answers to this questions, I divided the report into 3 parts: 
1. Periodic report for the days, months and years.
2. Locations report for the states and cities.
3. Advanced analysis for the key influencers.

## Skills/ Concepts demonstrated:
The following Power BI features were utilized:
- Bookmarking.
- Filters.
- Tooltips.
- Buttons.
- Powerquery.
- Page navigation.

## Data Source
The data was sourced from kaggle as a csv file. The data consists of only one table and shows the sales record of the store from 2014 to 2017. It consists of 22 columns and 9994 rows. The column headers included information like Order ID, Ship date, Ship mode, customer ID, Customer name, segment, city, state among others. The dataset was based on a store in the United States of America.

## Data transformation

After loading the table to power query, I did some transformations on the data like:
1. Changed the data types of some of the columns
2. I removed the Country column since we know that it's only one country involved.
3. I removed the row ID column.

## Visualization

The report consists of 3 pages:
1. Periodic report
2. Location report
3. Advanced Analysis

You can interact with the report [here](https://app.powerbi.com/groups/7947a12e-20ef-4e63-80fd-f5f47d010fd3/reports/26bdcae0-cb21-432c-a83b-687266cd5f2f/ReportSectione8fbf760089a179a7eb4)

![](periodic_report.png)

This is the dashboard to show how sales trended over time. It consists of a line chart to show sales trend over the months:

![](sales_trend_over_the_month.png)

Stacked column chart to show average sales by day of the week

![](averagesale_by_day_oftheweek.png)

Ribbon chart to show how customer segments rank

![](customer_segment_ribbonchart_powerBi.png)

Stacked column chart to show number of transactions by day of the week

![](numberof_transactions_by_day_oftheweek.png)

## Analysis

From the report, in year 2015, sales dropped to its lowest in February and rose to the highest point in November. Tuesdays usually have the highest average sales and   Wednesdays have the lowest number of transactions.


![](new_location_report.png)

This location report shows the states with the highest and lowest sales. It shows a stacked bar chart of top 10 states by sales:

![](top10statesbysales.png)

Stacked bar chart to show the bottom 10 states by sales

![](bottom10statesbysales.png)

Percentage of transaction shipments of the top 10 states

![](percentageof_transaction.png)

It also shows a map of sales by city in the United States of America.

## Analysis
From the report we learn that California brings the highest sales while Maine brings the lowest sales. We also deduce that most customers prefer the standard mode of shipment in the top 10 states.


![](advanced_analysis.png)
This report dives deep into the data to gather insights into the segments and how they influence sales overtime. It shows a decomposition tree that tells us the total sales for each year.

![](totalsalestree.png)

It also has a key influencers visual where we can drill through the segments and determine how they influence sales. There is also an ask your question button where you can ask questions concerning the report and gain more insights. ????

## Conclusion and Recommendation

- California has the highest number of sales for the year previewed :????
- Tuesday has the highest average sales 
- Maine has the lowest sales

## Recommendation
I recommend a method to increase sales in February.


![](hand-226358_1920.jpg)
