# Mydatabase_Homework3

## Practice with INNER JOIN 

### CREATE NEW TABLES AND INSERT VALUES

#### TABLLE1

`create table t_employee (

	deptno INT NOT NULL,
	
	empno INT  PRIMARY KEY,
	
	ename VARCHAR(20),
	
	job  VARCHAR(20),
	
	MGR  INT,
	
	Hiredate Date,
	
	sal    float,
	
	comm   float);
`

#### INSERT VALUES INTO TABLE1

`inset into t_employee2 (empno, ename, job, MGR, Hiredate, sal, comm, deptno) values 

   	(7369, "SMITH", "CLERK", 7902, "1981-03-12", 800.00, NULL, 20),
	
	(7499, "ALLEN", "SALESMAN", 7698, "1982-03-12", 1600, 300, 30),
	
	(7521, "WARD", "SALESMAN", 7698, "1838-03-12", 1250, 500, 30),
	
	(7566, "JONES", "MANAGER", 7839, "1981-03-12", 2975, NULL, 20),
	
	(7654, "MARTIN", "SALESMAN", 7698, "1981-01-12", 1250, 1400, 30),
	
	(7698, "BLAKE", "MANAGER", 7839, "1985-03-12", 2450, NULL, 10),
	
	(7788, "SCOTT", "ANALYST", 7566, "1981-03-12", 3000, NULL, 20),
	
	(7839, "KING", "PRESIDENT", NULL, "1981-03-12", 5000, NULL, 10),
	
	(7844, "TURNER", "SALESMAN", 7689, "1981-03-12", 1500, 0, 30),
	
	(7878, "ADAMS", "CLERK", 7788, "1981-03-12", 1100, NULL,20),
	
	(7900, "JAMES", "CLERK", 7698,"1981-03-12",  950, NULL, 30),
	
	(7902, "FORD", "ANALYST", 7566, "1981-03-12", 3000, NULL, 20),
	
	(7934, "MILLER", "CLERK", 7782, "1981-03-12", 1300, NULL, 10);	
`

#### TABLE2

`drop table if exsist t_dept;

create table t_dept (

    deptno INT PRIMARY KEY,
    
    dname VARCHAR(30),
    
    loc VARCHAR(50)
);`

#### INSERT VALUES INTO TABLE2

`insert into t_dept values

(10, "ACCOUNTING", "NEW YORK"),

(20, "RESEARCH", "DALLAS"),

(30, "SALES", "CHICAGO"),

(40, "OPERATIONS", "BOSTON")
;`





















