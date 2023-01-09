Write a query to update the Facebook advertiser's status using the daily_pay table. Advertiser is a two-column table containing the user id and their payment status based on the last payment and daily_pay table has current information about their payment. Only advertisers who paid will show up in this table.

Output the user id and current payment status sorted by the user id.

```advertiser``` Table:

| Columne Name  | Type          |
| ------------- | ------------- |
| user_id     | string         |
| status     | string         |


```advertiser``` Example Input:

| user_id | 	status |
| ------------- | ------------- |
|   bing 	  | NEW	      | 
|   yahoo	  | NEW	      | 
|   alibaba	| EXISTING	| 



```daily_pay``` Table:

| Columne Name  | Type          |
| ------------- | ------------- |
| user_id     | string       |
| paid        | decimal         |


```daily_pay``` Example Input:

| user_id | 	paid |	
| ------------- | ------------- | 
| yahoo 	| 45.00	| 
| alibaba	| 100.0	| 
| target	| 13.00 |
