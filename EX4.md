# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
SQL> create table employeee(empid number,empname varchar (20), dept varchar (10) ,salary number);

SQL> create or replace procedure insert_employeee_data AS

Procedure created.

SQL> begin


PL/SQL procedure successfully completed.

SQL> select * from employeee;
```

### Output:

### Result:
Hence the procedure using pl/sql is created successfully.
