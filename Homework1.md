# Mydatabase_homework1

## Database

### create database and show database

`create database company;`

`create database company1;`

`show databases;`

![p1.png](https://i.loli.net/2020/02/29/Fo3qZuIgf1PSbUN.png)

### drop database company1

`drop database company1;`

`show databases;`

![p2.png](https://i.loli.net/2020/02/29/L8CHPzlwEIDZ36T.png)

## Table

### create new table in the database

`use company`

`create table dept (
	deptno INT,
	dname VARCHAR(20),
	loc  VARCHAR(40)
);`

`create table dept1 (
	deptno INT,
	dname VARCHAR(20),
	loc  VARCHAR(40)
);`

`show tables`

![p3.png](https://i.loli.net/2020/02/29/z1YNahCdOAo6pKE.png)

### delect the table 

`drop table dept1`

`show tables`

![p4.png](https://i.loli.net/2020/02/29/gKfzasPo1rXOtCY.png)

### show the table(two ways) 

`describe dept` or `desc dept`
`show create table dept`

![p5.png](https://i.loli.net/2020/02/29/UFOdV9taeZETpfG.png)

