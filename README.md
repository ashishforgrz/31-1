# 1/06/2022

MySQL -
MySQL SELECT Statement -
SELECT * FROM table_name;

WHERE Clause -
SELECT * FROM Customers
WHERE Country = 'Mexico';

ORDER BY -
SELECT * FROM Customers
ORDER BY Country;

MySQL Delete -
DELETE FROM customers WHERE address = 'Russia'

MySQL Drop Table -
DROP TABLE customers

MySQL Update -
UPDATE customers SET address = 'Canyon 123' WHERE address = 'Valley 345'

MySQL Limit -
SELECT * FROM customers LIMIT 5

SQL MIN() and MAX() Functions
1. SELECT MIN(column_name)
FROM table_name
WHERE condition;

2. SELECT MAX(column_name)
FROM table_name
WHERE condition;
