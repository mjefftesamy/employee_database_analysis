# employee_database_analysis
# Purpose 
The purpose of this challenge is to Determine the total number of employees per title who will be retiring, and
Identify employees who are eligible to participate in a mentorship program and help the company get ready to replace those who will retire in the future by using SQL to study our database.

# Results
The relationship between our data is shown in the following ERD file:

![EmployeeDB png](https://user-images.githubusercontent.com/63277310/116483548-4815b200-a855-11eb-88e5-ebcc4daf6f5d.png)


Snippet of the group of position with employees that are likely to retire:
<img width="250" alt="2" src="https://user-images.githubusercontent.com/63277310/116484725-b2c7ed00-a857-11eb-973e-2d6a035f901b.png">



Given the company size of Pewlett Hackard, it was helpful to organize all the employee data in an ERD (entity relationship diagram). As you can see from the visualization of the relationship across the 6 core databases, there were a lot of relationships between employee data that needed to be established to analyze the pending retirement list of employees and mentorship eligibility. Also, as listed in the second figure, it is estimated that there will be about 10% of the overall employees that are ready to retire in the future.


# Recommendation
From the employee database there are over 300k employees. From the queries created, there are interim tables to filter the soon to retire employees which make up around 33k employees across 7 titles. For additional analysis we will need to find the overlap of how many of those soon to retire can train up the 1.5k unique employees that are eligible to be mentored. The recommendation to his manager would be to flag a potential problem since almost 10% of the Pewlett Hackard employees will retire soon but only 1% of employees are eligible to be mentored, which will cause a big gap for the company if all 10% decide to retire around the same time but only 1% will be trained up to fill the available position that we expect to have in the future.
