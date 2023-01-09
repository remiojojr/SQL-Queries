Assume you have the table below containing information on Facebook user actions. Write a query to obtain the active user retention in July 2022. Output the month (in numerical format 1, 2, 3) and the number of monthly active users (MAUs).

Hint: An active user is a user who has user action ("sign-in", "like", or "comment") in the current month and last month

```user_actions``` Table:

| Columne Name  | Type          |
| ------------- | ------------- |
| user_id     | integer         |
| event_id    | integer         |
| event_type  | string          |
| event_date  | datetime        |

```user_actions``` Example Input:

| user_id | 	event_id |	event_type |	event_date |
| ------------- | ------------- | ------------- | ------------- |
|445 	| 7765	| sign-in	| 05/31/2022 12:00:00
|742	| 6458	| sign-in	| 06/03/2022 12:00:00
|445	| 3634	| like	  | 06/05/2022 12:00:00
|742	| 1374	| comment	| 06/05/2022 12:00:00
|648	| 3124	| like	  |06/18/2022 12:00:00
