# SQL_training

SQL queries as exercises

# Query 1

## Goal
For each user_id, find the difference between the last action and the second last action. Action
here is defined as visiting a page. If the user has just one action, you can either remove her from
the final results or keep that user_id and have NULL as time difference between the two actions.
The table shows for each user all the pages she visited and the corresponding
timestamp.


# Query 2

## Goal
We have two tables. One table has all mobile actions, i.e. all pages visited by the users on
mobile. The other table has all web actions, i.e. all pages visited on web by the users.
Write a query that returns the percentage of users who only visited mobile, only web and both.
That is, the percentage of users who are only in the mobile table, only in the web table and in
both tables. The sum of the percentages should return 1.


# Query 3

## Goal
We define as power users those users who bought at least 10 products. Write a query that
returns for each user on which day they became a power user. That is, for each user, on which
day they bought the 10th item.
The table below represents transactions. That is, each row means that the corresponding user
has bought something on that date.


# Query 4

## Goal
We have two tables. One table has all $ transactions from users during the month of March and
one for the month of April.

Write a query that returns the total amount of money spent by each user. That is, the sum
of the column transaction_amount for each user over both tables.

Write a query that return day by day the cumulative sum of money spent by each user.
That is, for each day, from March 1st to April 30, we should have how much money each
user has spent in total until that day. Obviously, on the last day (April 30), the numbers
should match the numbers from the previous bullet point.



# Query 5

## Goal
We have two tables. One is user id and their signup date. The other one shows all transactions
done by those users, when the transaction happens and its corresponding dollar amount.
Find the average and median transaction amount only considering those transactions that
happen on the same date as that user signed-up.



# Query 6

## Goal
We have a table with users, their country and when they created the account. We want to find:
The country with the largest and smallest number of users
A query that returns for each country the first and the last user who signed up (if that
country has just one user, it should just return that single user)
