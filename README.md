COMMANDS: 
SQL>CREATE DATABASE Organization;  
Database Created 
SQL>CREATE TABLE Persons     
(     
); 
PersonID int,     
LastName varchar(255),     
FirstName varchar(255),     
Address varchar(255),     
City varchar(255)     
SQL>INSERT INTO Persons (PersonID, LastName, FirstName, Address, City)  VALUES 
('101', 'Erichsen', 'Tom', 'Street no-21', 'New York');   
SQL>INSERT INTO Persons (PersonID, LastName, FirstName, Address, City) 
VALUES ('102', 'Johnson', 'Marry', 'Old Street Road-43', 'California');  
SQL>INSERT INTO Persons (PersonID, LastName,FirstName)     
VALUES ('103', 'Steve','Rossy')    
SQL>INSERT INTO Persons VALUES ('104', 'Allen', 'Ketty', 'South Side Road', 'U.S.'); 
SQL> TRUNCATE TABLE Persons; 
SQL>SELECT * FORM Persons; 
Empty set (0.00 sec) 
Department of Computer Science and Engineering 
UCS1412 DATABASE MANAGEMENT SYSTEMS LABORATORY                                
II CSE 
SQL> CREATE TABLE customer_details( 
customer_id character varying(255) NOT NULL, 
customer_name character varying(255) NOT NULL, 
quantity integer NOT NULL, 
date_purchased date 
); 
Table Created. 
SQL> INSERT INTO public.customer_details( 
customer_id, customer_name, quantity, date_purchased) 
VALUES ('US1002','Kabir Khan','ABC', 2019-12-31);
