# SQL-query-commands-data-manipulation-and-find-errors
I write SQL commands to answer specific questions in Business Case Scenario.
![Screenshot 2022-11-17 150825](https://user-images.githubusercontent.com/118483157/202580409-ca6663f2-4fea-4db6-8bc5-3d8bead1deb9.png)
Using the same dataset, provide the SQL code and the output for this
query criterion.
a Provide an Excel sheet report of the total sum of payments made by
each customer in the payments table. Present it in ascending order.
There should be four columns: customer_id, first_name, last_name,
sum.
-You will need to join the customer & payment table.
-You will be using aggregate function, join and order by in
this query.
-Remember that when joining two tables with same column
names, if you put the column name alone (i.e. customer_id), it will
error out because it is ambiguous. You will have to put the table
name and column name (i.e. customer.customer_id)
There is a pgAdmin function for you to be able to extract/
download your query as a csv file.
Expected query output:
b Provide the SQL syntax and output of customer ids having an
average payment amount of less than 3.
Why would these SQL syntaxes fail?
a
SELECT first_name,last_name,district FROM customer

INNER JOIN address

ON address_id = address_id
b
SELECT customer_id,SUM(amount) FROM payment

GROUP BY customer_id

HAVING amount > 100
Answer the following business scenario questions. Provide the SQL code
and the output.
a One of the criteria for a customer to become part of the customer
loyalty program is that they need to have an accumulated payment
made to the DVD rental store of at least $200 or more. As a Data
Analyst, you need to provide a list of customer IDs with a total
accumulated payment of at least 200 or more.
Completion Criteria
For the first assignment 1A, you need to provide an SQL code (.csv file) for your
answer. For 2A, provide the SQL syntax and the output. For finding error in SQL (2A
and 2B), provide an explanation why the SQL syntax would error out. For 3A,
provide the SQL code and output.
