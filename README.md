# working_with_SQL

## Overview
The Purpose of this Analysis was to determine employees who had a high likelihood of retiring within the next year and determine who will be eligible for a mentorship program within the company to help with getting new hires up to speed.

## Results

- A table (retirement_titles) has been generated of all the employees that will be retiring soon. This list also shows all other positions that these individuals have had within the company prior to their current position.

![retirement_titles_sample](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/retirement_titles_sample.PNG)

- A table(retiring_titles) has been generated that shows the count of employees retiring and is grouped on each title.

![retiring_titles_sample](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/retiring_titles.PNG)

- A table(unique_titles) has been generated with each employee that will retire and shows their current title.

![unique_titles_sample](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/unique_titles_sample.PNG)

-  A table(mentorship_eligibility) has been generated of individuals throughout the company that can be contacted to engage in mentorship training for new employees

![mentorship_eligibility_sample](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/mentorship_eligibility_sample.PNG)

## Summary

Upon running a few more queries I found that their might be a few things of note to mention with the "silver tsunami". The first can be seen in the total employee count information that was collected and depicted below. When this total is compared to the total of amount of employees that are possibly going to retire within the next year, it becomes apparent that roughly 30% of the current employees will be retiring. This will mean that the company will need to make a serious pivot toward recruiting new hires.

Total Retiring
![total_retiring](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/total_retiring.PNG)

Total Employees
![total_employees](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/total_employees.PNG)

Upon looking at the total count of mentors per title type vs the amount of employees that need to be replaced based on retire count, the amount of mentors is severely under need. It may be worth the companies efforts to outsource some of the training efforts or ask retiring employees to spend some time developing training programs based on their experience.

Retiring Employees Count
![retiring_titles_sample](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/retiring_titles.PNG)

Mentor Count
![Mentor_count](https://github.com/drewabramo12/working_with_SQL/blob/main/Analysis%20Projects%20Folder/Pewett-Hackard-Analysis%20Folder/Images/mentorship_count.PNG)