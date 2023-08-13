# Task-1-SQL

#  **INTRODUCTION**

SQL also known as structured query language that is used for storing and processing information in relational database.
A relational database stores information in tabular form,in rows and columns.

A task was given to answer some basic sql questions, and this was done using PostgreSQL.

# Problem statement

To solve and provide solutions to the following  problems and questions.

1. Create a database called Student Record
2. Create the following tables in the database

  i.  Students info(Student ID, Gender,Name,Age,Subject)
   
  ii.  Health records(Student ID,Blood group,Height,Weight)
  
   iii. performance(Student ID,Score,Grade)

   >The ID has to be unique,
   >Where a student has no score,it should be '0' by default
   
   a.Add a constraint that prevents the ID and subject from taking null values.
   
   b.Change the column name"subject" to "course".

# Skills Demonstrated 

1. Creation of databases
2. Creation of table
3. SELECT* FROM tablename
4. Insert into
5. Values
6. Alter table
7. Alter column
8. Adding constraint

# Data analysis
I made use of  PGadmin4 in PostgreSQL to run SQL for the task.
After opening pgadmin4 ,click on the server ,then right click on the database and select create,type the name of the database and then save.

Then, create a table inside the database.
click on the database created ,then click on query tool ,create a table for students info, then type the following code in the query tool.


![Screenshot (2)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/798b27f6-345e-4735-86ef-fa5fd62d02b9)

Then insert some values into the table and type in SELECT * FROM the table_name

![Screenshot (5)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/9d3c249a-0577-43e9-8dc0-cfb8e9db9a2d)

Then creating health records table, 
![Screenshot (3)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/5f65c9c0-8d7b-4071-9f99-34567968dfac)

Inserting of values into health records table
![Screenshot (11)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/323252e6-c745-4225-b66e-3d69cc8027f2)

Creating performance table
![Screenshot (4)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/edb84718-da73-45f6-ac56-7cfce27a75b2)

Inserting values into the performance table
![Screenshot (15)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/024ff9b5-f4a8-49dc-a44e-c93277d6c3a5)


Where ID has to be unique
![Screenshot (12)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/5f086e01-627e-4a27-9c76-17c854f8eb88)

Adding a constraint that prevents the ID and subject from taking null values
![Screenshot (10)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/6f450fbe-be8a-4f61-8fff-83eb1a5fd979)

Changing column name 'subject' to 'course'
![Screenshot (7)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/a4b8c319-c189-4a46-a119-9fc67e8dea55)

Drop the 'Age' column from the students info table
![Screenshot (9)](https://github.com/Janefranceschisom/Task-1-SQL/assets/140454293/85164e8c-130c-4182-9189-93fc2451f57b)

# Conclusion

Getting introduced to SQL for the first time, had to understand the basic or starting point of working with SQL which is the 
^SELECT,FROM,INSERT INTO, VALUES,ALTER TABLE,ALTER COLUMNS.
Knowing the data type(integer,character,character varying,identity/serial,date,numeric,primary key,foreign key

Understanding and knowing these concepts is the first and most important step in tackling SQl







































   




   >
