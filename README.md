# SQL-and-Database-Testing-from-Scratch

# Introduction Data_Base
Data_Base is collection of tables
<br />
installing MySQL Workbench
![image](https://user-images.githubusercontent.com/98251620/151817838-0dfcde3f-e84a-465e-9bc7-0b70d7b442c9.png)
# SQL Queries
<br/>
#create a Database
<br/>
create database DataBase_Name;
<br/>
# Example:
<br/>
create database IT_Department;
<br/>
# pointing to Database by using "use" command
<br/>
use DataBase_Name
<br/>
Example:
<br/>
use IT_Department
<br/>
# Create Tables
<br/>
create table Emp(Employee_Name varchar(20),Employee_Id int,Employee_Dept varchar(20));
<br/>
	IT_Department	
Employee_Name	Employee_Id	Employee_Dept
Vijay	EMP1001	HR
Sanjay	EMP1002	IT
Ravi	EMP1003	Finance
![image](https://user-images.githubusercontent.com/98251620/151823527-ec2cbbb1-6460-41ba-97a0-7753c0d1ac4e.png)

# Regular Expression
<br/>
'%'--><br/>
'-'-->single character
<br/>
#use database <br/>
use IT_Department;
<br/>
Select * from employee;
<br/>
#print Employee_Name four letter
<br/>
select * from employee where  Employee_Name like 'V%';
# Sub queries
<br/>
select * from employee where  Employee_Name =(select Employee_Name from employee where Employee_Id="108");
![image](https://user-images.githubusercontent.com/98251620/151840336-357e17a4-42d0-49dd-9c4e-6ac213eb5142.png)


