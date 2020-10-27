# Pewlett Hackard Analysis

## Overview

Bobby and I, employees of the long standing company Pewlett Hackard, were tasked with future proofing 
the employee data, moving old CSV data into a PostgreSQL database. We created an entity relationship diagram to
properly design our database, as shown below.

![EmployeeDB.png](https://github.com/lindsera1/Pewlett_Hackard_Analysis/blob/main/EmployeeDB.png)

Using this ERD, we were able perform in depth analysis using a combination of joins, filters, counts and groupings in a systematic manner. 

### Purpose of the Analysis

The purpose of our analysis was to help our company draw insights from employee information to help them better
prepare for the "silver tsunami", the retirement of a massive number of baby boomers, and finding out the best
way to replace them in a timely and efficient manner. Our analysis yielded approximately 40,000 people would be 
retiring; we had to put together some specific strategies to proactively prepare.

## Results

Our company came up with a plan to establish a mentorship program, in which retirees would work part time in
training their juniors to fill in their positions as they would be leaving. To understand which job positions
would need to be filled, and who would be eligible to fill them, we created 2 tables.

+ The first table we created was a representation of who needed to be replaced by job title.
  This table gave us an idea of how many positions we would need to be filling, and for each job title.

![Job_Titles](https://github.com/lindsera1/Pewlett_Hackard_Analysis/blob/main/Screen%20Shot%202020-10-26%20at%209.55.38%20PM.png)

+ The second table informed us of empoloyees within a specificed age range (born in 1965) who would be eligible
  to replace these positions. 
  
+ Based from the information in both tables, we need at least 40,000 employees able to train and move up in 
position.

+ But what about the position they are leaving? Now we must ask, would it just be more profitable to hire new
employees, with a mix of employees already at Pewlett-Hackard?

## Summary

The great attention to detail in the early stages allowed us to use the information to draw the insights from
two major questions.
1. How many roles will need to be filled?
2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of 
Pewlett-Hackard employees?

After counting all the rows, there are only 2000 employees that would be able to move up, which is no surprise
since baby boomers made up the majority of the workforce. This means we will need to hire externally to be able
to replace all of the workers that are leaving Pewlett-Hackard.
