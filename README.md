![image](https://user-images.githubusercontent.com/104115546/209085591-34709ca6-dc01-4a44-ae51-103d19c75bda.png)

USE CASE

---Write a SQL statement to make a list for the salesmen who either work for one or more customers or yet to join any of the customer. 
--The customer, may have placed, either one or more orders on or above order amount 2000 and must have a grade, 
--or he may not have placed any order to the associated supplier.

Phase I

--1)create a stored procedures 
--2)push stored procedure data in a new table
--3)Data gather by including current time stamp in a new column

Phase II
4) create any primary key first on that table
5) once you get new data , upsert that data into final table using a primary key
6) Verify the upsert logic by insert and update statement by showing current time stamp column, once data get inserted it shows current time stamp.


Phase III
6) Create Final table
7) Verify the upsert logic using Merge statement as per current time stamp.

 

