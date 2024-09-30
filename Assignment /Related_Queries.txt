/*
DB details :

login : postgres
password :
server : localhost
port : 5432
Databse : postgres
Schema : landing

SQL Queries :
*/

Create Schema landing;

drop table if exists landing.employee;

CREATE TABLE IF NOT EXISTS landing.employee
(
    Id int,
    First_Name character varying ,
    Last_Name character varying ,
    DOJ date,
    Age int,
    Total_EXP int,
    Dept_id int,
    Dept_Name character varying ,
    Location character varying ,
    Salary int,
    Hike int,
    Contact int,
    Email character varying ,
    Project_id int,
    Project_Name character varying ,
    Primary_Skill character varying ,
    Secondary_Skill character varying 
);

INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (1,'Sanjay','Bhaskar','08-07-2007',32,15,101,'health_care','Hyderabad',25000,5,323154625,'talendtechsoloution@gmail.com',20156,'Cracto','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (2,'Ronald','Ford','02-22-2008',33,16,102,'Sales','Chennai',35000,44,65,'ronald@gmail.com',65458,'Practo','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (3,'George','Cleveland','04-26-2007',34,17,103,'IT','Bangalore',36000,8,100,'george@gmail.com',80566,'Alemeno','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (4,'	','Cleveland','05-19-2003',42,12,104,'BPES','Pune',57000,40,26,'theodre@gmail.com',2726363,'Alberto','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (5,'Ganesh','Rea','04-14-2005',24,13,105,'Finance','Noida',76000,24,79,'reagan@gmail.com',36466,'Alexian','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (6,'Ronald','Taft','03-01-2006',31,14,106,'Sales','Kolkata',77000,24,83,'taft@gmail.com',40126,'Alzerto','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (7,'Richard','Tyler','09-18-2005',36,13,107,'It','Kerala',72000,3,33,'richard@gmail.com',17466,'Alcido','Talend','Datawarehousing');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (8,'Ulysses','Reagan','07-03-2006',34,12,108,'BPES','Kochi',28000,12,83,'ulysses@gmail.com',3415263,'Citi','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (9,'Benjamin','Garfield','08-19-2003',32,16,109,'Finance','Chennai',29000,32,31,'benjamin@gmail.com',7714656,'Chattered','Talend','Datawarehousing');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (10,'Richard','Harding','11-12-2009',41,20,110,'Sales','Bangalore',90000,29,99,'harding@gmail.com',515521,'Philion','Talend','Datawarehousing');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (11,'Grover','Harrison','02-22-2002',36,20,111,'It','Hyderabad',52000,64,77,'grover@gmail.com',73156,'Phastro','Talend','Datawarehousing');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (12,'Jimmy','Truman','03-23-2001',38,16,112,'BPES','Kerala',64000,24,66,'jimmy@gmail.com',13263,'Zuseatro','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (13,'Herbert','Harrison','09-16-2005',35,11,113,'Finance','Kochi',29000,46,22,'herbert@gmail.com',51236,'Dreacki','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (14,'Theodore','Tyler','10-21-2003',25,14,114,'helath_care','Kolkata',53000,86,21,'tyler@gmail.com',12389,'Vyemank','Talend','Datawarehousing');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (15,'Zachary','Lincoln','12-20-2002',42,22,115,'health_care','Pune',71000,33,28,'lincoln@gmail.com',21415,'Lojakla','Talend','SQL');
INSERT INTO landing.employee(Id, First_Name, Last_Name, DOJ, Age, Total_EXP, Dept_id, Dept_Name, Location,	Salary, Hike, Contact, Email, Project_id, Project_Name, Primary_Skill, Secondary_Skill) VALUES (16,'Bil','Tyler','08-08-2001',47,22,116,'health_care','Noida',41000,4,28,'bill@gmail.com',2846556,'Fusion','Talend','Datawarehousing');

drop table if exists landing.employee_source;

CREATE TABLE IF NOT EXISTS landing.employee_source
(
    id integer,
    first_name character varying COLLATE pg_catalog."default",
    last_name character varying COLLATE pg_catalog."default",
    doj date,
    age integer,
    total_exp integer    
);

INSERT INTO landing.employee_source(
	id, first_name, last_name, doj, age, total_exp)
	VALUES (1,'Sanjay','Bhaskar','08-07-2007',32,15);
	
INSERT INTO landing.employee_source(
	id, first_name, last_name, doj, age, total_exp)
	VALUES (2,'Ronald','Ford','02-22-2008',33,16);

INSERT INTO landing.employee_source(
	id, first_name, last_name, doj, age, total_exp)
	VALUES (3,'George','Cleveland','04-26-2007',34,17);
	
INSERT INTO landing.employee_source(
	id, first_name, last_name, doj, age, total_exp)
	VALUES (4,'Theodore','Cleveland','05-19-2003',42,12);

drop table if exists landing.employee_target;

CREATE TABLE IF NOT EXISTS landing.employee_target
(
    id integer,
    dept_id integer,
    dept_name character varying COLLATE pg_catalog."default",
    location character varying COLLATE pg_catalog."default",
    salary integer,
    hike integer,
    contact integer
);

INSERT INTO landing.employee_target(
	id, dept_id, dept_name, location, salary, hike, contact)
	VALUES (1, 101,'health_care','Hyderabad',25000,5,323154625);
	
INSERT INTO landing.employee_target(
	id, dept_id, dept_name, location, salary, hike, contact)
	VALUES (2, 102,'Sales','Chennai',35000,44,65);

INSERT INTO landing.employee_target(
	id, dept_id, dept_name, location, salary, hike, contact)
	VALUES (3, 103,'IT','Bangalore',36000,8,100);
	
INSERT INTO landing.employee_target(
	id, dept_id, dept_name, location, salary, hike, contact)
	VALUES (5, 105,'Finance','Noida',76000,24,79);
	
Create Schema training;

CREATE TABLE training.employee_details (
	emp_id int4 NULL,
	emp_location varchar(100) NULL,
	emp_salary int4 NULL,
	emp_age int4 NULL
);

INSERT INTO training.employee_details (emp_id,emp_location,emp_salary,emp_age) VALUES
	 (1,'Mumbai',456456,25),
	 (2,'Hyderabad',3457656,27),
	 (3,'Hyderabad',6456456,26),
	 (4,'Mumbai',2345234,32),
	 (5,'Delhi',453454,15),
	 (6,'Mumbai',756764,62),
	 (7,'Hyderabad',5467567,23),
	 (11,'Patna',563453,89),
	 (12,'Banglore',7684651,45);