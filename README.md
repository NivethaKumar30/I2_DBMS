EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

AIM:

To create a student database and execute DDL queries using SQL.

DDL (Data Definition Language)

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

List of DDL commands:

CREATE: 
This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.

Query:

1) Create a table student with the following fieds rollno,name,age,address,phoneno.
SQL QUERY:
create table student(rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));

OUTPUT:

![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/97eb8110-e1f3-4167-ba2e-d08c561dfe21)


2) Change the above student table by adding another attribute department
SQL QUERY:
alter table student add department varchar(15);

OUTPUT:

![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/f034e62c-3b59-43d0-bec7-a2b6695e9de7)


3) Drop the student table
SQL QUERY:
drop table student;

OUTPUT:

![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/65fb017a-72a4-45e9-83e4-f068ade39149)



4) Delete the student table using truncate keyword
SQL QUERY:
truncate table student;

OUTPUT:

![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/f59a5ff3-e651-4e17-96c3-eea7d3bc5726)
                               

5) Rename the student table to mystudent
SQL QUERY:
rename table student to mystudent;

OUTPUT:

![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/e936ab75-c276-4d3f-8a99-166697befece)


RESULT :

Hence the student database has been created and the DDL queries are execueted using SQL .
