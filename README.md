# Pewlett-Hackard-Analysis.

## Overview of Project
 The purpose of this challange is to show how to create tables with SQL with using data from a company called Pewlett-Hackard which has many employees. The company wants to have a company wide retirement from people of the birthdate between 1952 through 1955. In this challange a database has been created to filter through those criteria to see who is on this list, their job title, and when they started. Also having a database and chart of people with job titles of current employees who can be in the mentors for the follwing new hires to replace the retirees.
## Results
### Retirment Chart
> - This first chart shows the employee's first and last name, with their title, and from and to dates. It uses the employees chart data to gather the information to use and sorts employees based on the birth date they were born on in this case it is between 1952 through 1955.
<img width="497" alt="Retirement_Title" src="https://user-images.githubusercontent.com/97326526/163705965-d53ea1d1-b3d8-4123-8ffe-dd572449cba9.PNG">

### Unique Chart
> - The next chart shows the employees that are still born between 1952 and 1955, its using the previous chart but is now showing employee number(emp_no), first and last name, and title. This chart also filters only those emloyees with a to date of 9999-01-01 which means currently employeed.
<img width="368" alt="Unique_Title" src="https://user-images.githubusercontent.com/97326526/163706321-70f03c3e-6259-4739-b9d3-c7fc67528e4f.PNG">

### Retiring Chart
> - In the third chart there is a *COUNT* function that will count which employees will be retiring. We will again be using the previous chart(**Unique Chart**). We sort this chart by using the highest count for each title.
<img width="166" alt="Retiring_Title" src="https://user-images.githubusercontent.com/97326526/163706599-bd32f0fc-673a-4158-872d-41138f86f645.PNG">

### Mentorship Eligibility Chart
> - In the final chart we use emp_no, first and last name, birth date, from and to date, and title. This chart uses the employees chart to get the data for birth date, this chart requires that it used employees that are born in the year of 1965. This chart is also sorted by the emp_no.
<img width="554" alt="Mentorship_Eligibility" src="https://user-images.githubusercontent.com/97326526/163706929-0e186a28-3b59-47f7-bc2a-354282685d63.PNG">

## Summary
  The amount of roles that will need to be filled for the "silver tsunami" program that the Pewlett-Hackard will be quite massive. From the data of employees that were born between 1952 and 1955 there will be 90,398 employees that will need to retire. This will require a large amount of time to replace and train all of the new employees for these roles to be replaced. For the mentorship eligibility program there are 1,940 employees, compared to the 90,398 roles that will need to be replaced this is only 2.15% of the current employees and that is if all the employees in the mentorship program are eligible. This would be very demanding on the employees in the mentorship program and may work. But if the use of the retiree force is used to train the next generation employee then the demand on the current employees will be less severe.
