# goit-rdb-hw-05 Relational Databases 

Tasks:

1. Write a SQL query that will display the order_details table and the customer_id field from the orders table, respectively, for each record field from the order_details table.
This must be done using a nested query in a SELECT statement.

2. Write an SQL query that will display the order_details table. Filter the results so that the corresponding record from the orders table fulfills the condition shipper_id=3.
This must be done using a nested query in the WHERE clause.

3. Write an SQL query nested in the FROM statement that will select rows with the condition quantity>10 from the order_details table. For the received data, find the average value of the quantity field - you should group by order_id.

4. Solve problem 3 using the WITH statement to create the temporary table temp. If your version of MySQL is earlier than 8.0, create this query in the same way as it is done in the synopsis.

5. Create a function with two parameters that will divide the first parameter by the second. Both the parameters and the return value must be of type FLOAT.
Use the DROP FUNCTION IF EXISTS construct. Apply the function to the quantity attribute of the order_details table.