## Last Week's Accomplishments

> Learning redis and mysql database.

> Examples:
> connecting the database, add, delete, and revise 

## This Week's Plan

> Start our project

> Examples: Begin creating the database for our own project

## Anything Blocking?

> Having problem connecting redis with php

> Examples: don't know how to use redis in php

## Notes

> 

## week 2
## Last Week's Accomplishments

> I did some practice about database: 
> 1)using try sytnx to create a table in database without posint error
> 2)storing data with small columns in to table, such as (province Text, population Integer, area Real)
> 3)using SELECT, WHERE, SUM, etc to change or get the date

> Examples:
> "CREATE TABLE Capitals(province TEXT, capital TEXT, population INTEGER)"

## This Week's Plan

> I want to store the course vs time table into databse.

> Examples: > "CREATE TABLE courses(time TIME, course1 TEXT, course2 TEXT, ... , coursen TEXT)"

## Anything Blocking?

> I'm familiar with mysql but still unfamiliar with redis and php.
> Need to get or access the data from the websit and change them into set.

> Examples: Our data need to be looked like this:
c=[
('Newfoundland and Labrador', 512930, 370501.69),
('Prince Edward Island', 135294, 5684.39),
('Nova Scotia' ,908007 ,52917.43),
('New Brunswick' ,729498 ,71355.67),
('Quebec' ,7237479 ,1357743.08),
('Ontario', 11410046, 907655.59),
('Manitoba' ,1119583 ,551937.87),
('Saskatchewan' ,978933, 586561.35),
('Alberta',2974807 ,639987.12),
('British Columbia' ,3907738 ,926492.48),
('Yukon Territory', 28674 ,474706.97),
('Northwest Territories' ,37360 ,1141108.37),
('Nunavut' ,26745 ,1925460.18),
]

## Notes

## week 3
## Last Week's Accomplishments

> We finished our first Auto-Grading demo which can scan a handwritten integer and store the result (a 10x10 lists of int which > >  represent color) into database.
> We finish our PPT for the presentation.
> I learn about a database class accomplished by our leader. This class can help to create or connect a database, create a table, insert data, change data, and so on.


 

> Examples:
> We use json to store the list: "CREATE TABLE Data (id INT, number INT, result json)"
> class Database(object):
    def __init__(self, my_user,my_password, my_host, my_database ):
        self.cnx = mysql.connector.connect(
            user=my_user,
            password=my_password,
            host=my_host,
            database=my_database
        )

## This Week's Plan

> I plan to furtherly learn some json and mysql knowledge which can inprove the efficiency

> Examples: > This is what I learn last week: "CREATE TABLE courses(time TIME, course1 TEXT, course2 TEXT, ... , coursen TEXT)"
            > Now this one is better:  "CREATE TABLE courses(time TIME, course_list json)"

## Anything Blocking?

> Time conflict with another project
> I participate in two project, autoGrading and Explore-Z-Westaland.

> Now my code work seperately with others code. I need to learn how to combind everything together. One part aims to scan the hand-written integer and give some data, and my part aims to load this data and store into database in a more efficient way.



## Notes

