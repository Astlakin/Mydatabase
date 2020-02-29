# Mydatabase_Homewok2

### alter table to add a column

`alter table dept
  add descri varchar(20);`

`desc dept;`

![p6.png](https://i.loli.net/2020/02/29/OpGDvhKuIE9Hljw.png)

### alter table to add a column in the first place

 `alter table dept
    add decri_head varchar(20)`
    
 `desc dept;`
 
![p7.png](https://i.loli.net/2020/02/29/OpetfiXoZJSqaBE.png)

### modify deptno from int to varchar

`alter table dept
  modify deptno varchar(20);`
  
`desc dept;`
  
![p8.png](https://i.loli.net/2020/02/29/2T3NBPZqJ4IWehH.png)
  
### not null constrains

`create table dept1(
	deptno int(20) not null,
	dname varchar(20),
	loc varchar(40)
);`
  
`desc dept1;`
  
![p9.png](https://i.loli.net/2020/02/29/xZmpf5DuPnwSqjy.png)
  
### primary key constrains

`create table dept1(
	deptno int primary key,
	dname varchar(20),
	loc varchar(40)
);`
  
 `desc dept1` 
  
![p10.png](https://i.loli.net/2020/02/29/cUgzPHIwm6vA5ZM.png)
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
