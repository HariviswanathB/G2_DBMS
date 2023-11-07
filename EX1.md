# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

# DATE:
4/8/23

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student (RollNo NUMBER,Name char(20),Age NUMBER,Address char(20),PhoneNo NUMBER);
```


### OUTPUT:
![image](https://github.com/HariviswanathB/G2_DBMS/assets/119103855/30ed3c22-f05d-47dd-a565-49a617780b01)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
 alter table student add Dept char(10);
```

### OUTPUT:
![image](https://github.com/HariviswanathB/G2_DBMS/assets/119103855/1a7c8382-e458-4c76-a605-6363770bd313)



### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```


### OUTPUT:
![image](https://github.com/HariviswanathB/G2_DBMS/assets/119103855/001558b4-279a-4d7b-b84b-789eb30d5b41)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
TRUNCATE TABLE student;
```


### OUTPUT:
![image](https://github.com/HariviswanathB/G2_DBMS/assets/119103855/b5530612-f329-4461-b59e-aed5a0a732ad)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```
 RENAME student to my_student;
```


### OUTPUT:
![image](https://github.com/HariviswanathB/G2_DBMS/assets/119103855/8395fd6a-0fee-4c66-8a5d-a54d52a059d6)

# RESULT:
Hence student database has been created and DDL queries are executed successfully using SQL.

