# Pewlett-Hackard-Analysis
SQL project
In this project, we need to solve problem conected with resignation. A lot of people might leave company because of retirement, we need to find out how many people, from what departments,what titles they have  and create idea to keep this people in the company
Firstly, we need to create EDR, to determine entry relationships, then to create new datebase and using Query Tool create tables according to our EDR, import data from csv
Starting out analysis with determining retirement eligibility. For this, we need to create query that returns us list of people with (birth_date BETWEEN '1952-01-01' AND '1955-12-31') AND (hire_date BETWEEN '1985-01-01' AND '1988-12-31'); from employees table and insert into retirement_info table, using COUNT we can find out how many people is going to retire. Then we can add the same information, but using join , we will add salary and to_date from salaries table.
In manager_info table, we will add info about manager who is goint to retire, divided by departments
The final list needs only to have the departments added to the current_emp table and save all in new dept_info table
The last one, we will create tailored list containig info about people who is going to retire from sales department, and then for sales+development departments
Finally, we can make a conclusion, there are a lot of people who is goint to retire in the company, the company needs an idea how to keep people for a more time, one of the decision is to propose the best employee to work partly or make them mentor for a newly coming people.Questions 

