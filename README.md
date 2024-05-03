# Coffee_Shop_Sales_Analysis_Excel.

I analyzed Data for Maven Roasters, a fictitious coffee shop operating out of 3 locations in NYC. I explored and analyzed the data in Excel using PivotCharts and a Dashboard.

## Table of Contents.
- [Business Task.](#business-task)
- [Source of Data.](source-of-data)
- [Data Manipulation Documentation.](data-manipulation-documentation)
- [Summary of Analysis.](summary-of-analysis)
- [Analysis Based on Coffee Shop Location.](analysis-based-on-coffee-Shop-location)
- [Relationships of data.](relationships-of-data)
- [Visualizations](visualizations)
- [Recommendations.](recommendations)
  
## Business Task.  
To better understand purchase behaviour and streamline operators from data colected from Jan 2023-Jun 2023

## Source of Data.
Coffee Shop Sales data was made available by Maven Analytics. The dataset is saved as a Microsoft Excel Workbook.

## Data Manipulation Documentation.
I added 6 columns to the dataset to help solve the business task i.e:
- Revenue - This helped me to analyze the financial perfomance of the coffee shop. Multiplied transaction_qty by Unit_Price  =D2*H2
- Month- This helped me to conduct analysis by Month. I used the Month Function =MONTH(B2) -B2 is transaction_date cloumn
- Month_Name- This column helped in visualiuzation as it is easier to interpret visualiztions with month name instead of number =TEXT(B2, "mmm")
- Weekday - helped to analyze transaction by day of week, =WEEKDAY(B2,2) 
- Weekday_Name- This made it easier to interprate the days of the week by name inteasd of numbers on the visualizations, =TEXT(B2,"ddd")
- Hour - this helped me analyze the transactions by time and have a better understanding of sales by the hour, =HOUR(C2)

## Summary of Analysis.

## Overall analysis of the three locations show that
- Total Revenue increased steadily each month but there was a slight dip on February.
- Coffee shops are busiest on weekday i.e Mon. - Fri.
- Busy hours for the coffee shops are from 7am-10am.
- Brewed Chai Tea is the most setting product for Maven Rosters 
- Coffee is the most selling product by Category
 
## Analysis Based on Coffee Shop Location.
## Astoria Location
- Total revenue increased steadily but a slight dip in Feb.
- Coffee shop is busiest on Monday and Thursday and slow on Satuday.
- Busy hours is from 7AM -10AM and from 11am-7am there is no huge variation when it comes to the number of transactions. This shows the store has good overall business activity.
- Brewed Chai Tea and Gourmet brewed codffee are the most sold products

## Hell"s Kitchen Location
- Steady growth of the coffee shop as Revenue increases each month.
- Busiest days are Tuesday and Friday and business is lowest on Saturday.
- There is a huge vatiation when it comes to the business activity by the hour. Shop is busiest from 8am-10am and from there there is a sudden drop. Slowest time for the shop 8pm.
- Barista Espresso, Brewed Chai Tea and Gourmet brewed coffee and the most selling products.
 
## Lower Manhattan Location
- Revenue increased steadily from February to June.
- Monday is the busiest day of the week then a sudden drop from Tuesday.
- Peak hours from 7am-10am and 7pm-8pm business is very slow.
- Barista Espresso, Gourmet brewed coffee and Brewed Chai tea are the best selling products.

## Relationships of data.
Data shows that there is a positive corrrelation when it comes to time of day and number of transactions. There is a spike of transactions in the morning from 7am-10am and a drop from 11 am which remains consistent until another sudden drop at 8pm.


## Visualizations.
Below is an Excel interractive Dashboard for the three coffee shop locations. 

[Coffee_Shop_Sales_Dashboard.xlsx](https://github.com/emychela/Coffee_Shop_Sales_Analysis_Excel/files/15200836/Coffee_Shop_Sales_Dashboard.xlsx)


## Recommendations.
1. ** Astoria Location** should extend opening hours to ** 8pm ** as number of transactions are still high at 7pm.
** Hell's kitchen ** and ** Lower Manhattan ** locations should close at ** 7pm ** as transactions are very low from 8pm.
3. Stores peak hours are from 7am-10pm, coffee shops should allocate more staff during this
hours.
4. Reduce number of staff on Saturday as this is not a busy day.
5. Processing times should be monitored during the peak hours to  endhace customers satisfaction.
6. Coffee, Tea, Bakery and Drinking chocolate products should be well stocked at the inventory as these are very fast moving products. 
