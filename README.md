# LITA_Class_Documentation
First Project while learning Data Analysis with the Incubator Hub
- Github set up was taken by Temidayo Ayeni, we explored using Github as an interface for creating a portfolio.
- The below is the note taken during the Github setup class.
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

...SELECT * FROM TABLE1

WHERE CONDITION = TRUE...

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

We had two data sets during the Excel class and these were used to carry out various analysis, some of which includes numbers and text editing in Excel, and summary of regional sales and revenue of a company.

Below are some of the highlights from the three weeks of intensive teachings, including class notes and class work. 

The most important of the highlights for me is his quote by Brian Herbert, which says, **"the capacity to learn is a gift, the ability to learn is a skill, and the willingness to learn is a choice."** I am glad that I made the choice to learn.

#### Day 1 - Week 1 (Introduction, Data entry, Excel functions 1)
![Basics of Data Analysis - 19 Aug 2024 - Muhsin Hameed](https://github.com/user-attachments/assets/78b5b959-2b07-4baa-b3fc-ec678a6f209e)

#### Day 2
![Tips for Success in Data analysis](https://github.com/user-attachments/assets/4fe325f7-6092-4e9a-8e9e-c1ac38796b6c)

#### Week 2 (Excel functions 2, Data clean up)
![Basic Excel Function 1](https://github.com/user-attachments/assets/2a789003-b93d-4988-a829-a78bec6927ff)

![Basic Excel Function 2](https://github.com/user-attachments/assets/cc3ccad0-e64f-4ba6-b38f-37cdfc46314a)

#### Week 3 (Excel functions 3, Pivot table and chart)

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
...values ('parameters' as above)...

...drop table employee... *Used for deletion of a whole table in SQL*

---delete from employee... *Used to alter a parameter/delete only an item or few from a table in SQL*
...where staffid  = 'parameter'...

...TRUNCATE... *This will delete all rows/content of table and free up space* 
Example ...TRUNCATE table employee...

...IDENTITY... *This helps to auto-increase/generate the primary key, for instance, the identity (1,1) means the primary key starts from 1 and increases by 1*
*To insert more records into a table, you do not need to specify the column names as long as the new records will follow exactly the same format from the existing records*

...UPDATE... *This updates a record you already have on a table to a new one, like the example below*
...update Salary
set salary = 7056999.9994
where staffid = 'AB401'...

...ALTER... *This adds an additional column into a table like the example below*
...alter table EMPLOYEE...
add State_of_Origin varchar (50)...

CASE WHEN syntax is used to input huge amount of data into an existing table when ALTER cannot be used

Other SQL Clauses, Operators Views and Case When were taught in class, but isnt included in this summary.





### Power BI (Business Intelligence)

Temidayo Ayeni is the man for the job when it came to teaching PowerBI. He took us through the basics to the detailed aspect of the session.

We worked on a list of datasets, one of them had to do with evaluating the attrition rate of a company using the HR data.

Visual expressions from the classworks are listed below.

[PowerBI Classwork.pdf](https://github.com/user-attachments/files/17532222/PowerBI.Classwork.pdf)

![First dashboard](https://github.com/user-attachments/assets/62eb1593-4a5a-4a7f-b4b4-b19a9ea32bc9)

![Region by Revenue](https://github.com/user-attachments/assets/c9175db3-4818-470c-b901-c1198a581066)

![Matrix_Table_difference](https://github.com/user-attachments/assets/9ee678fb-4833-42f0-8a64-6df8277f5eb2)

![Map visual](https://github.com/user-attachments/assets/60c2f3f0-a616-4e91-8128-846e0ca44e00)

![HR Analytics](https://github.com/user-attachments/assets/ff5aaf80-e899-4df5-987d-ee9054152c92)

![HR Analytics Pg 2](https://github.com/user-attachments/assets/f7490461-a4d9-4899-93c8-e89632ccc644)


