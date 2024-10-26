# LITA_Class_Documentation
First Project learning Data Analysis with the Incubator Hub
- Taken by Temidayo Ayeni. using Github as an interface for creating a portfolio.
- Note: The below is the note taken during the Github setup class.
- The portfolio of work done during the LITA Data Analysis course is down the page. [DATA ANALYSIS - LITA - THE INCUBATOR HUB](#data-analysis--lita--the-incubator=hub)

## LITA_Class_Documentation
### LITA_Class_Documentation
#### LITA_Class_Documentation
Hashtags denotes a heading, the number of hashtags determines the size of the heading

## Project Title: 
---
3 dashes gives your heading an underline

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[How to upload or attach a document or visuals](#how-to-upload-or-attach-a-document-or-visuals)

[Data Visualization](#data-visualization)

### Project Overview
Insert anything

### Data Sources
Insert anything

### Tools used
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. Data Cleaning
  2. Analysis
  3. Visualization
- SQL - Structured Query Language for querying of data
- Github for Portfolio building
To create indentations, just put hyphen in front of your lines, and for the next set of indentation, you can use numbering.
If you do not put hyphens, you list will be written in a block of statement/paragraph.

### Data Cleaning and Preparations
In the initial phase of data cleaning and preparations, we perform the following actions;
1. Data loading and inspection
2. Handling missing variables
3. Data cleaning and formating

### Exploratory Data Analysis
EDA involves the exploration of data to answer some questions about the data such as;
- What is the overall sales trend?
- Which product are top sellers?
- What are the products on peak sales?

### Data Analysis
This is where we include some basic lines of code or queries, or even some of the DAX expressions used during analysis. 

To write a code, we must start and end with 3 dots as seen below

... SQL
SELECT * FROM TABLE1
WHERE CONDITION = TRUE
...

There are various syntaxes that can be used in Github, for instance;
2 stars in front, your character in between and two stars at the end is BOLD syntax,
1 star in front, your character and one star at the end is the ITALICS syntax


### How to upload or attach a document or visuals
Click on repository name, it takes you back to the home page, click on the + sign beside Go to file tab, click upload file and follow other instructions.

### Data Visualization
Put in your images here, go to your folder, click and drag and drop.
![Screenshot 2024-09-02 114717](https://github.com/user-attachments/assets/a29f7caf-7d48-401b-a9a5-57b71c1fa392)

If you want to be artistic with your work, press the full colon : and try to type what you want, and this will give you a list of emojis you can add to your work 
🥇

You can also create a table by yourself, using the pipe symbols | as seen below, the dashes closes the heading columns

| Heading 1 | Heading 2 | Heading 3|
|-----------|-----------|----------|
| Table 1   | Table 2   | Table 3  |

You can create an outline of headings and put it immediately after the project title, this will help you when working so as not to keep scrolling down a very long page of work done. See outline up this page.

To do the outlines, open a square bracket, copy and paste your headings exactly the way it is typed on your document and close the square bracket, then open a parentesis, insert #, write the headings in small caps, use hyphen - to create space in the headings and then close the parentesis. 

### RECOMMENDATIONS

# DATA ANALYSIS - LITA - THE INCUBATOR HUB

## Project Title: Data Analysis course summary

### Introduction
A message popped up on a RCCG youths' WhatsApp group and it was a free training for ladies seeking knowledge in tech. I did not hesistate to jump on the wagon. I filled the application and the rest is story. Thanks for the initiative brought about by Pastor Folu'Adeboye in conjuction with The Incubator Hub and Ladies In Tech Africa (LITA).
![Welcome Message](https://github.com/user-attachments/assets/c219e159-3587-4cda-8d4c-e372592f257f)

### Microsoft Excel
Before the data analysis course began, I could do basic data entry using Excel and that is about it. Thanks to the detailed instructor in person of Hameed Muhsin (ID), he made learning Excel come easy. 

We started the course learning the basics of data analysis (everything we should know), data entry using Excel sheet and workbook, then moved on to deeper things like Excel functions, and the class wrapped up with pivot tables, charts and presentation of results.

We had two data sets during the Excel class and these were used to carry out various analysis, some of which includes

Below are some of the highlights from the three weeks of intensive teachings, including class notes and class work. 

The most important of the highlights for me is his quote by Brian Herbert, which says, **"the capacity to learn is a gift, the ability to learn is a skill, and the willingness to learn is a choice."** I am glad that I made the choice to learn.

#### Day 1 - Week 1 (Introduction, Data entry, Excel functions 1)
![Basics of Data Analysis - 19 Aug 2024 - Muhsin Hameed](https://github.com/user-attachments/assets/78b5b959-2b07-4baa-b3fc-ec678a6f209e)

#### Day 2
![Tips for Success in Data analysis](https://github.com/user-attachments/assets/4fe325f7-6092-4e9a-8e9e-c1ac38796b6c)

#### Day ? - Week 2 (Excel functions 2, Data clean up)
![Basic Excel Function 1](https://github.com/user-attachments/assets/2a789003-b93d-4988-a829-a78bec6927ff)

![Basic Excel Function 2](https://github.com/user-attachments/assets/cc3ccad0-e64f-4ba6-b38f-37cdfc46314a)

#### Day ? Week 3 (Excel functions 3, Pivot table and chart)

### Structured Query Language (SQL)

During the three weeks when the SQL guru, Femi Ayodele took us, we learnt how to use the structured query language to query data and answer questions from a database. We also saw during his teachings the similarities and somehow, connectivity between Excel functions and SQL queries.

Some of the queries written and used during this session are seen below, starting with creating a database.

...create database LITA_DB... *This creates a database in the SQL server management studio, and create table below creates a table in the databse created*

...CREATE TABLE Employee (
staffid varchar (10) not null,
FirstName varchar (255) NOT NULL,
SecondName varchar (255),
Gender varchar (10),
Date_of_Birth date,
HireDate datetime,
primary key (staffid)
)...

...select * from Employee... *This selects all and displays the content of the employee table created*

...insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)... *This helps to insert parameters/values into the created table as appropriate*
...values ( 'parameters' as above)...

...drop table employee... *Used for deletion of a whole table in SQL*

---delete from employee... *Used to alter a parameter/delete only an item or few from a table in SQL*
...where staffid  = 'parameter'...

truncate table employee

--------12/09/2024----------------------------

------identity in SQL -----

CREATE TABLE PERSON (
personid int identity (1,1) primary key not null,
personname varchar (255) not null,
age int
)
insert into PERSON (personname, age)
values ('saidu', 45),
('adebanjo', 49),
('olorunda', 33),
('martha', 88),
('sandi', 100),
('jackson', 22),
('okunola', 19),
('esther', 45)

select * from PERSON

------Insert more records into Employee table-------

insert into [dbo].[Employee]
values ( 'AB200', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB405', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB282', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB278', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09'),
( 'AB240', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB299', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB268', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB286', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB270', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09')

select * from [dbo].[Employee]

---- to create second table call SALARY TABLE-------
CREATE TABLE Salary (
salary_id int identity (1,1)not null,
Staffid varchar (255),
firstname varchar (255),
lastname varchar (255),
department nvarchar(max),
salary decimal (10, 3) ---(10: precision, 3:scale)
)

select * from [dbo].[Salary]

-----insert records into Salary table-------------

insert into salary (staffid, FirstName, lastname, Department, Salary)


values ( 'AB401', 'ayan', 'olakun', 'Information Tech.', 45000.45),
( 'AB212', 'okorie', 'mercy','Account',500000.99999),
( 'AB223', 'joshua', 'chukwuemeka', 'Human Resources',100560.9339999),
( 'AB234', 'sanni', 'ibrahim', 'Sales and Marketing',845688.99),
( 'AB254', 'mercy', 'olanipekun', 'Account',8889.999999),
( 'AB249', 'johnson', 'mercy', 'Information Tech.',234000.90909090),
( 'AB298', 'ayomide', 'halleluyah', 'Logistics', 678000.991999),
( 'AB260', 'deborah', 'justin', 'Logistics',900099.00697969),
( 'AB281', 'wale', 'olanipekun', 'Information Tech',873093.2344)

insert into [dbo].[Salary]
values ( 'AB200', 'ayomide', 'halleluyah', 'Human Resources',45699.8585),
( 'AB405', 'deborah', 'justin', 'Account',898349.900222),
( 'AB282', 'wale', 'olanipekun', 'Sales and Marketing',362636.564848),
( 'AB278', 'shukurat', 'lasisi', 'Logistics',100000.464647),
( 'AB240', 'johnson', 'mercy', 'Information Tech',3855590.9890093),
( 'AB299', 'ayomide', 'halleluyah', 'Account', 8585858.9292),
( 'AB268', 'deborah', 'justin', 'Human Resources',76767.93939)

----SUM, COUNT, MAX, MIN, AVERAGE---------------------------------

SELECT SUM(Salary) AS TOTALSALARY FROM Salary

SELECT AVG(Salary) AS AVERAGESALARY FROM Salary

SELECT COUNT(Staffid) AS EmployeeCount FROM EMPLOYEE

SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary

-----update--------

update Salary
set salary = 7056999.9994
where Staffid = 'AB401'

-----------------------13/09/2024------------------------
--update staff name-----

select * from [dbo].[Employee]

update employee
set secondname = 'Endurance'
where staffid = 'AB405'

----UPDATE DEPARTMENT-------

select * from [dbo].[Salary]

UPDATE SALARY
SET department = 'Information Tech.'
where Staffid = 'AB234'

UPDATE SALARY
SET department = 'Information Tech.'
where Staffid = 'AB240'


SELECT * FROM Salary
WHERE Staffid = 'AB281'

----CREATE ADDITIONAL COLUMN INTO EMPLOYEE TABLE-------

ALTER TABLE EMPLOYEE
ADD State_of_Origin varchar (50)

select * from employee

UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB268'

-----create another table call PAYMENT TABLE------
CREATE TABLE Payment (
paymentid int identity (1,1) primary key,
Account_No bigint not null,
staffid int,
Bank varchar (255) default 'Zenith Bank',
Payment_Method varchar (50) check (Payment_Method = 'Cash' or Payment_Method = 'Transfer')
)

alter table payment
alter column staffid varchar (30)

select * from Payment

insert into Payment (account_no,staffid,payment_method )
values (2033030303, 'AB200', 'transfer'),
(2123459910, 'AB401',  'transfer'),
(2034562240, 'AB254',  'cash'),
(2234556303, 'AB212',  'transfer'),
(2033037703, 'AB249',  'cash'),
(2033030303, 'AB298',  'cash'),
(2455657503, 'AB260',  'transfer'),
(2045595953, 'AB281',  'cash'),
(2033030303, 'AB273',  'transfer'),
(2077778903, 'AB299',  'transfer'),
(2033030301, 'AB286', 'transfer'),
(2123459911, 'AB260',  'transfer'),
(2034562241, 'AB270',  'cash'),
(2234556302, 'AB104',  'transfer'),
(2033037705, 'AB268',  'cash'),
(2033030306, 'AB270',  'cash'),
(2455657509, 'AB300',  'transfer')

insert into Payment
values (2198773830, 'AB299',  'GT bank', 'transfer'),
(2024656569, 'AB405',  'Access bank', 'cash'),
(2222444933, 'AB200',  'Fidelity bank', 'transfer'),
(5674842300, 'AB278', 'Access bank', 'transfer'),
(2222444933, 'AB200',  'GT bank', 'transfer'),
(2034537300, 'AB278', 'Access bank', 'transfer')

------those receive their salary by cash-----
SELECT * FROM Payment
WHERE Payment_Method = 'Cash'

select * from Payment
where Payment_Method = 'TRANSFER'

SELECT COUNT(*)  AS ZenithStaff FROM Payment
where Bank = 'Zenith Bank'

SELECT COUNT(*)  FROM Payment
where Bank = 'GT BANK'

SELECT COUNT(*)  FROM Payment
where Payment_Method = 'Transfer'

SELECT COUNT(*)  FROM Payment
where Payment_Method = 'cASH'

---Analysis on Employee table------

select * from Employee

select count(*)  from employee 
where state_of_origin  = 'Kano'

select count(*)  from employee 
where gender  = 'male'

select * from Salary

select count(*)  from Salary
where department  = 'Human Resources'

select top 5 * from Salary

select * from Salary
where salary > 700000

select Staffid, salary from Salary
where salary < 700000


select max(salary) from Salary

select min(salary) as min_salary from Salary


### Power BI (Business Intelligence)
[PowerBI Classwork.pdf](https://github.com/user-attachments/files/17532222/PowerBI.Classwork.pdf)

![First dashboard](https://github.com/user-attachments/assets/62eb1593-4a5a-4a7f-b4b4-b19a9ea32bc9)

![Region by Revenue](https://github.com/user-attachments/assets/c9175db3-4818-470c-b901-c1198a581066)

![Matrix_Table_difference](https://github.com/user-attachments/assets/9ee678fb-4833-42f0-8a64-6df8277f5eb2)

![Map visual](https://github.com/user-attachments/assets/60c2f3f0-a616-4e91-8128-846e0ca44e00)

![HR Analytics](https://github.com/user-attachments/assets/ff5aaf80-e899-4df5-987d-ee9054152c92)

![HR Analytics Pg 2](https://github.com/user-attachments/assets/f7490461-a4d9-4899-93c8-e89632ccc644)


