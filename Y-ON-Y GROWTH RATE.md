Assume you are given the table below containing information on user transactions for particular products. Write a query to obtain the year-on-year growth rate for the total spend of each product for each year.

Output the year (in ascending order) partitioned by product id, current year's spend, previous year's spend and year-on-year growth rate (percentage rounded to 2 decimal places).

user_transactions Table:

| Columne Name  | Type          |
| ------------- | ------------- |
| transaction_id     | integer         |
| product_id         | integer         |
| spend              | decimal          |
| transaction_date   | datetime        |


Example Input:
| transaction_id | 	product_id |	spend        |	transaction_date |
| ------------- | ------------- | ------------- | ------------- |
|     1341   	|     7765	| 1500.60	| 05/31/2022 12:00:00
|     1423  	|     6458	| 1000.20	| 06/03/2022 12:00:00
|     1623	  |     3634	| 1246.44 | 06/05/2022 12:00:00
|     1322	  |     1374	| 2145.32	| 06/05/2022 12:00:00
