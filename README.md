# store_annual_report_2022
OBJECTIVE:
----------
This store owner want to create a annual sales report for 2022, so that they understand their custumer and grow the sales next year.

TOOLS USE:
----------
1.Excel 

STEPS:
------
1.Data import from protection view to normal
2.Data Cleaning
3.Create pivot table
4.Create Pivot chart
5.Connect Slicer
6.Design Report
7.Insights
8. Final Conclusion

STEP 1:
-------
* Go to review and unprotect the worksheet.
* Insert password if worksheet is password protected.

STEP 2:
-------
* See and understand the columns name so that it will easy to understand data and find insights.
* Filter the all data and see is their any null value in any column, if number of null value is negligible then remove those raws. 
* In above data their is no null value.
* In column "Gender" somewhere "Men" and "Women" are mentions as "M" and "W" respectively.
* Replace 'M' with 'Men' and 'W' with 'Women' using replace function(Ctrl+f).
* In "Quantity" column replace 'One' With 1 and 'Two' with 2 using sameprocess as above.
* Add new column of 'Age Group' and categories as
   1. Senior for 50 and above
   2. Adult for 30 to 49
   3. semi adult for 20 to 29
   4. Teenager for 19 and below
* Add another new column from of 'Month' from date column.
    =TEXT(date,"format")
    eg. =TEXT(12/12/2022,"mmm")  (we get month in short form 'Dec'.for full spelling write "mmmm" in format)
     
STEP 3:
-------
Insert pivot table from "insert menu".
These are some question whose answer we have to find using pivot table and show them as chart in report.

1.Compare the sales and orders using single chart?
ans. Put 'Order id' and 'amount' column in value count and 'Month' column in raw we get the pivot table (Sales vs Order)

2.which month get highest sales and orders?
ans. From the chart of above sales vs order we can easily ee in chart "march" 2022 has highest sales and orders.

3.Who purchased more men or women in 2022?
ans. For this we have to create a pivot table of sales based on gender.
     Put 'Gender' column in raw and 'Amount' in value count then we create a visual pie chart and see women purchased more.

4.What are the different order status in 2022?
ans. Delivered,Cancelled,Refunded,Returned are order status.

5.List top 5 states contributing to the sales?
ans. 'States' column in raw 
    'Amount' column in Value count
    and go to value filter and use top 10 option change the number to top 5.
    i.e MAHARASHTRA
        KARNATAKA
        UTTAR PRADESH
        TELANGANA
        TAMIL NADU
        
6.Relation between age and gender based on number of orders?
ans. 'Gender' in raw
    'Age group' in column
    and 'order id' in value count
    adult women have more order of aprox 34%.

7.Which channel is contributing to maximum sales?
ans. 'Channel' in raw 
     'order id' in value count
     Amazon --- 35%
     Myntra --- 23%
     flipkart --- 21.5%

8.Highest selling Category?
ans. 'Set' has highest sale

STEP 4:
-------
Create a pivot chart for each pivot table from analyze pivot table menu 
* Go to pivot chart
* Select chart
* Paste chart in report sheet

ADD SLICER:
-----------
* Add slicer in report to connect all data.
* Right click on slicer and "report connection" to connect slicer to all chart.

DESIGN REPORT:
--------------
Customize ccolour and design of report as you want but remember thee points
* Chart should be visible
* colour combination should be familier
* Try to use easy chart instead of complex one.

INSIGHTS:
----------
* Maximum sales month of the year is march.
* womens are more likely to buy as compare to mens.
* 92% items are delivered and only 3% canclled that means sales is good.
* MAHARASHTRA, KARNATAKA, UTTAR PRADESH, TELANGANA, TAMIL NADU are top 5 sales states.
* Adult women on 30 to 49 are more active customers.
* Amazon, Myntra and flipkart give approx 80% of sales.

FINAL CONCLUSION:
-----------------
To improve sales target womens customer of age 30 to 49 living in MAHARASHTRA, KARNATAKA, UTTAR PRADESH by Showing ads, offers, coupons discount and relative products available on amazon myntra and flipkart.
-----------------------------------------------------------------------------------------------------------------------------------------------------
THANK YOU
-----------


  
