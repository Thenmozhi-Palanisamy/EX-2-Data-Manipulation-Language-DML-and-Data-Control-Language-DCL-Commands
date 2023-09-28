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

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/92f21693-07dc-4cf3-8b66-2f5c902cb23b)


### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/33e02c72-6924-40f1-835e-b6b0eddb1bab)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/5b869b07-e4b7-4193-b469-ac4b3c6d3c86)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/87157693-e7d9-42ba-96f9-650b295f6082)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/017c3fa6-422d-47ee-9e18-2d1378ed2e32)



### OUTPUT:

### Q4)	List the names of Clerks from emp table.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/19ac3dfd-d74d-4980-865a-5548c7bfbd7f)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/5486bcaa-a410-4a4f-875c-f00dc2641103)



### Q5)	List the names of employee who are not Managers.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/244bea09-8543-4aff-8f8a-f3cc1f7e6ec9)



### OUTPUT:


![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/43f8d9cd-e3ab-4684-a094-e4a5436e6549)


### Q6)	List the names of employees not eligible for commission.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/b3da1769-8933-48ab-bc40-37e1637fd2d7)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/a90e176e-1a3c-43b4-b932-90e6847ff488)



### Q7)	List employees whose name either start or end with ‘s’.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/56c4fed6-3f18-432c-8b3a-5aed4e822e33)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/f483cff6-9a89-42d2-ac9c-9add790764f0)



### Q8 Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/e4f63a5f-c267-48ce-84a2-0b83145635cd)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/de88b962-7340-4c05-93e1-3c8acc98bf82)



### Q9) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/6957206c-a314-405d-ac6f-c7630c59c789)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/d95ed9b2-85a4-451c-a059-838c8ae06034)



### Q10)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/441afe56-a533-424c-a737-2aa9329f7b7d)


### OUTPUT:


![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/979adeb2-b4d2-47f7-8dfd-50e220148bb4)


### Q11) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/6b14232c-7d69-44df-8231-69b0805fb8a4)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/c12c1f6d-ba14-4d35-87f1-b4cafffccfd7)


### Q12) Find number of rows in the table EMP

### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/149915c2-c9f4-40a6-8721-d125f7282c02)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/394a4d54-c7fe-47a8-9e01-14e8d8ee591c)



### Q13) Find maximum, minimum and average salary in EMP table.

### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/122c8be1-9481-424f-bf25-210758db3598)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/5c6c4fd8-970e-477e-8ac9-58d0ef62fb5d)



### Q14) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/008a885c-d206-4888-99f2-4808acb7266b)



### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/95198708/0a208d02-a538-4e73-9fd7-2529a554b28e)

## RESULT:
Thus the  Data Manipulation Language (DML) Commands and built in functions in SQL
