We Designed a Power BI dashboard to understand AtliQ hardware goods sales trend.
in order to do analysis for it, we used 2 programs: MySql, Power Bi

we firstly started with transforming data which contains:
1- values in INR and USD currency, so we made themm all in on currency
2- there are some blank culomns so we deleted the related rows
3- there are problem in the writing of USD and INR so we deleted the wrong ones
4- we have amounts which is less than 0, and amount can't be less than 0, so we filtered them

# and by this we finished the data cleaning (transforming) step

after that, we need to duild data model and link them all and we did that in data model in Power Bi

# Now he step of building Dashboard:
the main elements that we need to highlit it in our report are: 
Revenue, Sales Quantity, the year and Cy date (month exactly)
then from those elements we extracted: 
1- Revenue by customer name
2- sales Qty by customer name
3- Revenue by market
4- sales by market
5- top 5 customers by revenue
6- top 5 customer products
7- Revenue Trend

then we added total margin and we calculated:
1- profit % by market
2- profit contribution
3- profit contribution % by market
4- Revenue contribution by market 
5- a table that contains customer name, revenue, revenue contribution %, profit margin contribution, profit margin

# This dashboard could help in increasing the revenue at least by 7% in the next quarter.
# Sales_Insight_business_analyst
