EXP 1:DATA DEFENITION LANGUGE COMMANDS IN RDBMS


AIM:

To create a student database and execute DDL queries using SQL.

DDL (Data Definition Language)

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

List of DDL commands:

CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.

Query:
Create a table student with the following fieds rollno,name,age,address,phoneno.

SQL QUERY:
CREATE TABLE STUDENTT(rollno INT PRIMARY KEY,name1 VARCHAR(255),age INT,address VARCHAR(255),phoneno VARCHAR(15));

OUTPUT:
![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/5c7837c2-a5b3-48da-9a5e-4fb90dbeda8a)


Change the above student table by adding another attribute department

SQL QUERY:
ALTER TABLE STUDENTT ADD dept VARCHAR(50);

OUTPUT:
![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/e88de8b9-b987-425b-99b0-89b9654ce574)


Drop the student table
SQL QUERY:
DROP TABLE STUDENTT;

OUTPUT:
![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/6179d333-8ba2-4be0-889f-b120df1ee7b3)


Delete the student table using truncate keyword
SQL QUERY:
TRUNCATE TABLE STUDENTTT;

OUTPUT:
![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/498396e5-204a-4cb9-87a7-45348e14440c)


Rename the student table to mystudent
SQL QUERY:
ALTER TABLE STUDENTT RENAME TO mystudent;

OUTPUT:
![image](https://github.com/NivethaKumar30/I2_DBMS/assets/119559844/d8f9fc04-f12d-4b00-b205-d91f0063eb50)


