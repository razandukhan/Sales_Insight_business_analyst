# Sales_Insight_business_analyst
We designed a Power BI dashboard to understand AtliQ hardware goods sales trends.
in order to do analysis for it, we used 2 programs: MySql, Power Bi

we first started with transforming data which contains:
1. values in INR and USD currency, so we made them all in one currency
2. there are some blank columns so we deleted the related rows
3. there are problems in the writing of USD and INR so we deleted the wrong ones
4. we have amounts which are less than 0, and amount can't be less than 0, so we filtered them

## and by this we finished the data cleaning (transforming) step

after that, we need to build a data model and link them all and we did that in the data model in Power Bi

## Now the step of building the Dashboard:
the main elements that we need to highlight in our report are: 
Revenue, Sales Quantity, the year and Cy date (month exactly)
then from those elements, we extracted the: 
1. Revenue by customer name
1. sales Qty by customer name
1. Revenue by market
1. sales by market
1. top 5 customers by revenue
1. top 5 customer products
1. Revenue Trend

then we added the total margin and calculated:
1. profit % by market
1. profit contribution
1. profit contribution % by market
1. Revenue contribution by market 
1. a table that contains customer name, revenue, revenue contribution %, profit margin contribution, profit margin

## This dashboard could help in increasing the revenue by at least 7% in the next quarter.
# Sales_Insight_business_analyst
