# Pewlett-Hackard-Analysis
![img](QualifiedNauticalBluet-mobile.gif)

Resource:https://gfycat.com/qualifiednauticalbluet-chuck-parks-music

### Overview of the analysis:
Using SQL techniques, we need to determine the number of retiring employees by title and identify which employees are eligible to participate in the mentorship program. We used employees born between January 1 1952 and December 31, 1955.

### Results: 
The COUNT function was useful to create a Retiring Titles table that shows the number of retirement-age employees by job title. It is interesting to see that there were only a handful of manager positions. This could be a good opportunity for HR to investigate why there were so few managers. Also, retiring titles show us the majority of the employees of retirement age have senior titles.

![img](retiring_titles.png)


To identify the employees who are eligible to participate in a mentorship program, I created a Mentorship Eligibility table that holds the employees who were born between January 1, 1965, and December 31, 1965. On the other hand, One of the most interesting things in the table down that most of these employees have senior titles.
![img](https://github.com/Edgarhv/Pewlett-Hackard-Analysis/blob/02f6bcd73ee02922adad47c61f67b4edfe59fc12/mentorship_eligibilty.png)

### Summary:

According to the retiring title table, there are 90,398 roles will need to be filled as the employees begin to retire. If we want to create a new query we can the total number of employees of the company. we can see how many jobs will remain filled and how many need to be filled. Also, we will see that there are not exactly be enough people in the workforce to take care of the tasks or even come close to the amount of experience to fill these roles so quickly. Finally, there are not enough mentors to effectively train the next generation and I would recommend expanding the eligibility date for mentors in order to increase the number of mentors.
