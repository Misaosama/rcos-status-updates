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

## week4 and week5 (about Oct 12-Oct 27)
## Last Week's Accomplishments

> I worked on the demo and presentation of Explore-Z-Wasteland
> 1) I create monster class. In that class, a monster has health, attack, armor, magic resistance, etc. I use redis hash_table to store informations of each monster.
> 2) I accomplished a reword computation. After a monster was killed, a player can get some reword from that monster. I use random to compute what and how many items can a player get as rewords.
> 3) I finished the movement function for players, which could change the position of a player and determine whether this movement is valid or whether a player encounter a monster after a step.


> Examples:
> This is an example of a particuliar monster database.
> “Monster_name”:
> health:	           500
> armor: 	           10
> Magic_resistance:	 5
> damage:	           30
> wealth (gold):	    50 
> reward_1:	         Item1
> reward_2:	         Item2
> Reward_3:        	 Item3
> Reward_4:	         Item4 

## This Week's Plan

> I'm going to learn some back-end knowledge on python which may be used for Autograding.
> Also I'm tring to see if I can also create the fight system or weapon class in Explore-Z-Wasteland

> Examples: Flask and Jinja2.

## Anything Blocking?

> For the character or player in Explore-Z-Wasteland, we may not create player class, and instead, we will store the information in database directly. Each time a player login in, his or her information will be read from database. It seems we do not need to create a player class.

> Examples: Just store a player's health, mana, wealth, experience, etc on database.

## Notes

> 


