# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```

## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b32bceb5-9f0f-4c30-b27f-c4375e677f46)



### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/3fd9b83b-a6e7-4e47-b0cb-f2815bbbae95)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/15e1ebf0-899f-4589-aee8-0ea4570cefba)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/ad0c2970-47bc-4591-8f4b-a295a38b092d)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/72faf04a-7d00-4070-8b1b-433f67d05a51)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b697b096-ba16-4329-ac6b-d015128fd061)


### Q5)	List the names of Clerks from emp table.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b1f05e5a-a309-424e-b910-cb103f5413e3)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/f8bc5ab3-f99d-400e-aa3f-c1f6c4a06c5d)



### Q6)	List the names of employee who are not Managers.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/01b12f80-95f7-431c-95a7-4470c12c4a72)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/0cf2a6ad-398f-4d29-bebb-c31a84334347)


### Q7)	List the names of employees not eligible for commission.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/42336775-5693-4b45-93b4-f60e6b80183c)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/8f6da561-78ad-4573-9c8b-406de97e5e19)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/63e34f73-6454-4c79-bafd-403fbb23ca66)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b947469e-7ad5-4b63-966b-652d7d2c8c0f)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/ea09fd51-d67f-4b14-abc7-7093026e69dd)

### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b3a0080f-b755-412a-b631-2c8484061c1c)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/d96047cf-2bbb-4e35-9509-b6948cc69eff)


### OUTPUT:

![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/dc101670-2467-428c-bf52-734adc718334)

### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b195dae7-d5fb-405b-b0fd-8f3cac28497c)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/8366de8d-6502-4a70-a202-8540b84db42c)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/ab24e141-c401-4a54-92a5-6b83dec1f504)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/5b712bd1-29b3-465b-93c0-5076e2aa9128)

### Q13) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/c7af2c72-f955-4cfa-925e-e1768eff217b)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/c5628317-f034-4f88-951c-339f05cd7079)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/b50b8a48-eb40-42e5-9fd4-c638757f67ba)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/fa7dd8b3-a982-48f3-b03e-bd7f9152564e)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/16718b1f-b7d9-4fbf-97df-0b4a4e74466c)


### OUTPUT:
![image](https://github.com/DhanushPalani/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121594640/123c7d66-c434-4809-8e89-85fefdf37f24)
