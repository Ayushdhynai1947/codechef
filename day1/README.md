-- q1_all_product
-- Write a query to output Products table.

-- Table name: Products

-- product_id	product_name	price	category
-- 1	Laptop	999.99	Electronics
-- 2	Desk Chair	149.99	Furniture
-- 3	Smartphone	599.99	Electronics
-- 4	Notebook	2.99	Stationery
-- 5	Headphones	89.99	Electronics
-- 6	Coffee Maker	49.99	Appliances
-- 7	Standing Desk	249.99	Furniture
-- 8	Tablet	399.99	Electronics
-- 9	Mouse	19.99	Electronics
-- 10	Water Bottle	12.99	Stationery

#######################

- q2_High_price

Task
Write a query to find all product_name and category that have a price greater than 100.00 from the Products table.

Table name: Products

product_id	product_name	price	category
1	Laptop	999.99	Electronics
2	Desk Chair	149.99	Furniture
3	Smartphone	599.99	Electronics
4	Notebook	2.99	Stationery
5	Headphones	89.99	Electronics
6	Coffee Maker	49.99	Appliances
7	Standing Desk	249.99	Furniture
8	Tablet	399.99	Electronics
9	Mouse	19.99	Electronics
10	Water Bottle	12.99	Stationery
Expected columns
product_name
category

###############################

Average Salary
Task
Write a query to calculate the average salary across all companies combined. Rename the column as avg_salary.
Table name: Works

employee_id	company_name	salary
1	TechCorp	75000.00
2	InnovateLtd	62000.50
3	HealthPlus	54000.75
4	EduWorks	48000.00
5	GreenTech	68000.00
6	TechCorp	80000.00
7	InnovateLtd	66000.20
8	HealthPlus	50000.10
9	EduWorks	51000.00
10	GreenTech	72000.00
Expected column
avg_salary




###########################

Task
Write a query to retrieve the department_name and location of people who live in location that starts with 'S'.
Table name: departments

department_id	department_name	location
1	Human Resources	New York
2	Research and Development	San Francisco
3	Sales	Los Angeles
4	Marketing	New York
5	Customer Support	Boston
6	Finance	Austin
7	IT Support	Seattle
8	Product Management	San Francisco
9	Quality Assurance	Los Angeles
10	Legal	Boston
Expected column
department_name
location