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
q3_Locate People
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

q4_Locate People.sql
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



###########################################
q5_Distinct Companies.sql

Task
Write a query to select all the distinct companies (company_name) in the Works table.
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
Expected Column
company_name




#############################
q6_Fiction Collection Size.sql

Task
Write a query to find the total count of books whose genre is Fiction.
Note: Output column name should be fiction_count.

Table name: Books

id	title	author	genre	price	published_year
1	The Great Gatsby	F. Scott Fitzgerald	Fiction	10.99	1925
2	1984	George Orwell	Dystopian	15.99	1949
3	To Kill a Mockingbird	Harper Lee	Fiction	12.99	1960
4	The Catcher in the Rye	J.D. Salinger	Fiction	14.99	1951
5	Brave New World	Aldous Huxley	Dystopian	13.99	1932
6	The Hobbit	J.R.R. Tolkien	Fantasy	9.99	1937
7	Moby Dick	Herman Melville	Fiction	18.50	1851
8	War and Peace	Leo Tolstoy	Historical	20.00	1869
9	The Picture of Dorian Gray	Oscar Wilde	Fiction	11.50	1890
10	The Alchemist	Paulo Coelho	Fiction	16.00	1988
11	Fahrenheit 451	Ray Bradbury	Dystopian	12.50	1953
12	The Chronicles of Narnia	C.S. Lewis	Fantasy	14.00	1950
13	The Handmaid's Tale	Margaret Atwood	Dystopian	15.50	1985
14	A Tale of Two Cities	Charles Dickens	Historical	13.00	1859
15	Little Women	Louisa May Alcott	Fiction	9.50	1868


Expected column
fiction_count