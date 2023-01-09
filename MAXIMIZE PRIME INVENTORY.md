Amazon wants to maximize the number of items it can stock in a 500,000 square feet warehouse. It wants to stock as many prime items as possible, and afterwards use the remaining square footage to stock the most number of non-prime items.

Write a SQL query to find the number of prime and non-prime items that can be stored in the 500,000 square feet warehouse. Output the item type and number of items to be stocked.


```inventory``` Table:

| Columne Name       |      Type       |
| -------------      | -------------   | 
| item_id           | integer         |
| item_type          | string        |
| item_category         | string          |
| square_footage        | decimal       |

```inventory``` Example Input:

| item_id | 	item_type |	item_category |	square_footage |
| ------------- | ------------- | ------------- | ------------- |
|   1374 	| prime_eligigble	| mini refrigerator | 68.00
|   4245	| not_prime	      | standing lamp	    | 26.24
|   2452	| prime_eligible	| television	      | 85.00
|   3255	| not_prime	      | side table  	    | 22.60
|   1672	| prime_eligible	| laptop    	      | 8.50
