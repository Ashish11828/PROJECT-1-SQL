# PROJECT-1-SQL
Project to help you practice everything that you learnt about data manipulations. Imagine you are hired by a Supermarket chain as a database analyst. Your initial task is to create a database of customers.
-- Create a table 'customer'
CREATE TABLE customer(
Id INT,
Name TEXT,
Age INT,
Address text
);



Insert Into customer(Id,Name,Age,Address)


-- Insert data into the table 

VALUES(1, 'John Smith', 25,  '123 Main St'),
(2, 'Sarah Johnson', 30,'456 Broadway'),
(3, 'Michael Brown', 45, '789 5th Ave'),
(4, 'Jessica Davis', 28, '321 Elm St'),
(5, 'David Lee', 35,  '555 Park Ave');

-- Output the entire table
select * from customer;
