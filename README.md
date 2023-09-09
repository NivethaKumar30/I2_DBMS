EXP 1: DATA DEFENITION LANGUGE COMMANDS IN RDBMS
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
image

Change the above student table by adding another attribute department
SQL QUERY:
ALTER TABLE STUDENTT ADD dept VARCHAR(50);

OUTPUT:
image

Drop the student table
SQL QUERY:
DROP TABLE STUDENTT;

OUTPUT:
image

Delete the student table using truncate keyword
SQL QUERY:
TRUNCATE TABLE STUDENTTT;

OUTPUT:
image

Rename the student table to mystudent
SQL QUERY:
ALTER TABLE STUDENTT RENAME TO mystudent;

OUTPUT:
image

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 14 forks
Report repository
Releases
No releases published
Packages
No packages published
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
