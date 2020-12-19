
HOW TO RUN:
-----------

1. Install Visual Studio Code

2. Change file path in terminal to where you are downloading project

3. Check if tkinter is installed in python

4. Open login.py file to view the code

5. Open the terminal and type python login.py to run program.

"You have to create your own database".

Database:
------------

 Database name: grocery_store
 Tables: admin_register,employees,invoices,products
 
1.admin_register
+----------+-------------+------+-----+---------+----------------+
| Field    | Type        | Null | Key | Default | Extra          | 
+----------+-------------+------+-----+---------+----------------+
| id       | int         | NO   | PRI | NULL    | auto_increment |
| username | varchar(50) | YES  |     | NULL    |                |
| password | varchar(50) | YES  |     | NULL    |                |
+----------+-------------+------+-----+---------+----------------+

2.employees
+---------------+-------------+------+-----+---------+----------------+
| Field         | Type        | Null | Key | Default | Extra          |
+---------------+-------------+------+-----+---------+----------------+
| employee_id   | int         | NO   | PRI | NULL    | auto_increment |
| username      | varchar(50) | NO   |     | NULL    |                |
| password      | varchar(50) | NO   |     | NULL    |                |
| employee_name | varchar(50) | NO   |     | NULL    |                |
| contact_num   | bigint      | NO   |     | NULL    |                |
| address       | varchar(50) | NO   |     | NULL    |                |
| aadhar_num    | bigint      | NO   |     | NULL    |                |
+---------------+-------------+------+-----+---------+----------------+

3.invoices
+------------------+-------------+------+-----+---------+-------+
| Field            | Type        | Null | Key | Default | Extra |
+------------------+-------------+------+-----+---------+-------+
| bill_number      | int         | NO   | PRI | NULL    |       |
| date             | datetime    | NO   |     | NULL    |       |
| customer_name    | varchar(50) | NO   |     | NULL    |       |
| customer_contact | bigint      | NO   |     | NULL    |       |
+------------------+-------------+------+-----+---------+-------+

4.products
+----------------+---------------+------+-----+---------+----------------+
| Field          | Type          | Null | Key | Default | Extra          |
+----------------+---------------+------+-----+---------+----------------+
| product_id     | int           | NO   | PRI | NULL    | auto_increment |
| category       | varchar(50)   | NO   |     | NULL    |                |
| sub_category   | varchar(50)   | NO   |     | NULL    |                |
| product_name   | varchar(50)   | NO   |     | NULL    |                |
| stock_quantity | int           | NO   |     | NULL    |                |
| MRP            | decimal(10,2) | NO   |     | NULL    |                |
+----------------+---------------+------+-----+---------+----------------+

Software Requirements:
----------------------

1. python 3.9

2. MySQL Database

3. Visual Studio Code 
