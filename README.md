Lab 2 - Databases, SQL and Use Cases
=

Main Objectives
==========
- Students should be able to write basic SQL queries
- Learn how use a database design and a data dictionary
- Go through the Phase1 requirements and start working on defining the Bakery Outlet application: Define actors and 


Due Date:
==========
**January 20, 2022** by the end of the lab session :)

Important Note
= 
 In this lab, you have only **2 checkpoints** to validate with one of the teaching team members. 
 
Checkpoints will be graded as follows:

* Checkpoint 1: 70 points
* Checkpoint 2: 30 points

Part 1. SQL Querying
==========
### Narrative and directives

The Western Pennsylvania Chess Club (WPCC) is a small chess club that provides an opportunity for  scholastic players throughout the area to come together for tournaments, classes and times of open play. 

The main goal of WPCC is to help each child learn and succeed in playing chess as much as possible while at the same time stressing that in the end good character and sportsmanship are more important than good chess. 

In this lab, we will use query the tables of the WPCC database, already designed. The goal is to refresh our SQL skills. 

Access the data dictionary and the database design of the WPCC databse available in the Lab 2 repository.  

Review the contents and ask any questions regarding the database you might have to the TAs before proceeding.

**Note**: We are providing you with a set of [slides] summarizing the basic and most used SQL queries. Make sure you refer to these slides and to [Google](https://www.google.com/) to brush up your SQL skills.


### Queries

Write the SQL queries to answer the following requests:

1. Get an alphabetized list of all the students (last name, first name) along with their grade and rating. **[10 points]**

2. Get the average grade and rating from WPCC students in the system. **[10 points]**

3. For a given tournament (for example purposes, assume tournament_id=1), get a master list of all the students (last name, first name) along with their grade, rating and section. The list should be ordered by section (use section id to order this, not name) and then by rating (descending order) within each section.**[10 points]**

4. Get the list of all payments (date of payment formatted as mm/dd/yy and amount of payment) received for a particular family (assume family_id=1).**[10 points]**

	**Hint**: Think of using the [DATE_FORMAT()](https://www.w3schools.com/sql/func_mysql_date_format.asp) function, that formats a date as specified.

5. Get the list of all the different locations used to host WPCC classes in 2008 along with a count of the number of times the site was used that year. Do not include any locations that did not host any events in 2008 and order the list by the number of events hosted (in descending order).**[10 points]**

6. Get an alphabetized list of locations that are in the WPCC system but did not host any tournaments or classes in 2008.**[10 points]**

7. Get an alphabetical list of all users who have not served as a lead instructor for a class. Also include a count of the number of classes they helped in as an associate instructor.**[10 points]**

- - -
# <span class="mega-icon mega-icon-issue-opened"></span> Stop!

**Checkpoint 1**. Show a CA the SQL queries you wrote to answer each question.
- - -

Part 2. Baking Outlet: Actors
==========
In this part, you will mainly work on one part of your Phase 1. 

1. Read the [baking outlet narrative](https://github.com/S22-67-272Q/67-272Q-P1/blob/main/baking_outlet_narrative.pdf) very carefully.

2. Identify the main actors of the Baking Outlet system. You will have to create the Actor List table by filling the [template](https://github.com/S22-67-272Q/67-272Q-P1/blob/main/HL_use_cases_template.doc) provided in Phase1 repository.

3. Make sure you indicate the complexity level of each of the actors you identified, as well as a description of the actor and which actions/operations would she/he be doing in the Bakery outlet application.

- - -
# <span class="mega-icon mega-icon-issue-opened"></span> Stop!

**Checkpoint 2**. Show a CA the Actor List Table you created.
- - -




