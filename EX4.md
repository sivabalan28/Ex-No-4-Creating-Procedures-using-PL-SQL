# Ex. No: 4 Creating Procedures using PL/SQL

# Date

### AIM: 
To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
# CREATE TABLE
```
create table employeetable1(id int,name char(20),dept char(20),salary int);
```
# CREATE PROCEDURE
```
create or replace procedure insert_employeetable1_data AS
BEGIN
INSERT INTO employeetable1(id,name,dept,salary)
values (1,'john','HR',50000);
INSERT INTO employeetable1(id,name,dept,salary)
values (2,'joe','IT',60000);
INSERT INTO employeetable1(id,name,dept,salary)
values (3,'Bob','Finance',55000);
COMMIT;
END;
/
```
# CALL PROCEDURE
```
begin
insert_employeetable1_data;
end;
/
```
# DISPLAY TABLE
```
select * from employeetable1;
```

### Output:
![272547593-16bef0a4-b247-4e78-9eff-fd899f3f581f](https://github.com/sivabalan28/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/113497347/5dae21e2-3675-40fa-920f-8b12741a6789)
![272547726-f5001a5a-7830-47b3-8a1d-abf896ac02c1](https://github.com/sivabalan28/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/113497347/3225294e-9ad2-41fe-8429-8946e4d934bd)
![272547797-ef149411-281c-4e29-abeb-6f13743c0521](https://github.com/sivabalan28/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/113497347/24de9c51-4f1c-4cf3-b4b8-b98b4c509168)


### Result:
Hence the procedure using pl/sql is created successfully.
