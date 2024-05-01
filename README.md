# Coffee_Shop_Sales_Analysis_Excel.

I analyzed Data for Maven Roasters, a fictitious coffee shop operating out of 3 locations in NYC. I explored and analyzed the data in Excel using PivotCharts and a Dashboard.

## Table of Contents.
- [Business Task.](#business-task)
- 

## Business Task.  
To better understand purchase behaviour and streamline operators from data colected from Jan 2023-Jun 2023

## Source of Data.
Coffee Shop Sales data was made available by Maven Analytics. The dataset is saved as a Microsoft Excel Workbook.

## Data Manipulation
I added 6 columns to the dataset to help solve the business task i.e:
- Revenue - This helped me to analyze the financial perfomance of the coffee shop. Multiplied transaction_qty by Unit_Price  =D2*H2
- Month- This helped me to conduct analysis by Month. I used the Month Function =MONTH(B2) -B2 is transaction_date cloumn
- Month_Name- This column helped in visualiuzation as it is easier to interpret visualiztions with month name instead of number =TEXT(B2, "mmm")
- Weekday - helped to analyze transaction by day of week, =WEEKDAY(B2,2) 
- Weekday_Name- This made it easier to interprate the days of the week by name inteasd of numbers on the visualizations, =TEXT(B2,"ddd")
- Hour - this helped me analyze the transactions by time and have a better understanding of sales by the hour, =HOUR(C2)

  ## Summary of Analysis

  Overall analysis of the three locations show that 


