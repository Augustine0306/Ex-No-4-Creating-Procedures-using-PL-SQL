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
create table employee_1(empid number,empname varchar(10),dept varchar(10),salary number);
```
```
create or replace procedure insert_employee_data as
begin
insert into employee1(empid,empname,dept,salary)
values(1,'LEANN'','HR',50000);
insert into employee1(empid,empname,dept,salary)
values(2,'YOGI','Finance',55000);
insert into employee1(empid,empname,dept,salary)
values(3,'AUGUS','IT',60000);
commit;
end;
/
```
### Procedure call:
```
begin
insert_employee_data;
end;
/
```
### Display table:
```
select * from employee_1;
```
### Output:
![image](https://github.com/Augustine0306/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119404460/7167f4e5-5aa0-485c-8fcf-f7138f258c5c)

### Result:
THE PROGRAM HAS BEEN IMPLEMENTED SUCCESSFULLY
