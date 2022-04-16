# Pewlett Hackard Analysis

## Overview of Project

### Purpose
The purpose of this project was to use PostgresSQL to analyze Pewlett Hackard data to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. Then we could use this information to develop a plan for when those eligible decide to retire.

## Results
•	Below is the ERD (Entity Relationship Diagram) created to help visualize the connection between the data sources.

![EmployeesDB.png](https://github.com/SZapata4/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png?raw=true)

•	From the process of analyzing the data sources given we created the retirement titles table seen below. After looking at this table and adding the positions you can see that Pewlett Hackard has 72,458 employees that could retire very soon. That is a very large portion of its work force and could be a problem soon.

•	Another observation made from this table is that most of the people at the retirement stage of their career hold Senior positions. That will also be a tough problem to overcome do the requirements need to fill such a position causing a smaller hiring pool.

![CountPerTitle.png](https://github.com/SZapata4/Pewlett-Hackard-Analysis/blob/main/CountPerTitle.png?raw=true)

•	After creating the mentorship eligibility table (below is sample) and finding that there are only 1,550 employees eligible one can see there is a large gap between possible retirees and suitable replacements in the company.

![MembershipEligibilty.png](https://github.com/SZapata4/Pewlett-Hackard-Analysis/blob/main/MembershipEligibilty.png?raw=true)


## Summary
To summarize this analysis I am going to answer the two questions below that help give some solutions to the problems that Pewlett Hackard is facing.

How many roles will need to be filled as the "silver tsunami" begins to make an impact?

Looking at the retiring titles table and adding those together there are 72,458 positions that will need to be filled. In order to slow the process of employees retiring Pewlett Hackard should look at possibly adding an incitive for these retirement eligible employees to stay on longer to provide more time to find suitable replacements. Another option would be possibly having these employees come back as part time workers after they retire to help bridge the gap as well.

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

No, there are only 1,550 employees eligible for the mentorship program. That means Pewlett Hackard will most likely have to start a serious hiring initiative to help fill all the soon to be vacant positions.


## Resources
Data Sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

Software: SQL, PostgreSQL, pgAdmin

