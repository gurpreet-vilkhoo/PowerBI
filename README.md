### Financial Dashboards


 ### Sales, Income and Financial Simulator Dashboard

 
 ![Revenue and Margin Analysis](https://user-images.githubusercontent.com/80466173/111428223-3a7cf080-871d-11eb-92cb-a2985bda2a6c.gif)

![Income Statement Analysis](https://user-images.githubusercontent.com/80466173/111428345-613b2700-871d-11eb-983f-ea84cb109a00.gif)

![Financial Simulator](https://user-images.githubusercontent.com/80466173/111428408-7748e780-871d-11eb-9a32-9fb8eb3903de.gif)



 ### Revenue Dashboard
#### Business Case:
ABC company is recording transactions in three different excel workbooks. One contains details about customers; other two contains details of transaction as Invoice Headers and Invoice details.
The purpose is to create Revenue dashboard
##### The following steps were done to create the revenue dasboard:-
Step 1: Get Data and transform
Using Power- BI, Import the given data set, rename the tables as Customers, OrderHeaders and Orderdetails and transform it if required.
Step 2: Build Model
Create the Data Model and establish relationships
Step 3: Add Columns and Measures
(a)	CALCULATED COLUMN in OrderDetails
Total Revenue (in dollars) = Unit Price * Quantity
Total Cost (in dollars) = Unit Cost * Quantity
Total Margin (in %age) = (Total Revenue – Total Cost)/ Total Revenue. 
(b)	Calculated columns in OrderHeaders: Year, MonthNo and MonthName
(c)	Optimize the data Model
•	Sort the MonthName by MonthNo. 
•	Hide the various columns in all three tables which are not required in the report view
(d)	Add the following measures
i)	2007 Revenue ( in Dollars) 
ii)	2006 Revenue (in Dollars)
iii)	2007 vs 2006: Difference of 2007 Revenue and 2006 Revenue
Step 4: Use proper visualizations to create a “Revenue report” 
(a)	Add a proper title for the page using Text box
(b)	Show :
i.	KPI: All three measures (using Multi Row Card)
ii.	Revenue and Cost by Month (using combo chart)
iii.	Revenue by Top 10 customers (using column chart)
iv.	Revenue, Cost and Average Gross Margin for each Customer (using Table)
(c)	Add slicers for years  and set the following visual interactions:
i)	Year should filter – Column (iii) and table (iv) only
ii)	Column chart (iii) should not affect Table (iv).
![Revenue Dashboard](https://user-images.githubusercontent.com/80466173/111251020-6ec8b200-8634-11eb-950f-906369e1136a.png)


