# Georgia-salary-gender-differences
Differences and trends in salaries based on gender at Georgia state institutions

# SUMMARY

I analyzed salaries from the Open Georgia database which has information about the salary, type of profession, institution, and year ranging from 2010-2018. I used the genderize API to obtain information on gender based on first name. I found that in general, women employees have lower salaries than their male counterparts, by over 40%. The reason for this is two-fold:

1) The proportion of women in low paying jobs (substitute teacher, 24%) relative to the total number of women in the dataset is significantly higher than the relative proportion of men (13%) in low paying jobs. Whereas the relative proportion of men in high paying jobs (professor, 3%) is significantly higher than the relative proportion of women (1%) in professor jobs.

2) The percent difference between salaries of men and women in the same profession increases as the salary increases.

# Fig1
Large discrepancy between median male and female salaries over a number of occupations across the state of Georgia
Closer look reveals that a significantly larger portion of female employees are in lower paid jobs (substitute teachers) as compared to male employees

# Fig2
With increasing salary by profession, the salary (percent!) difference between male and female employees gets larger.


# Data Sources:
State of Georgia salary information 2010-2018
http://www.open.georgia.gov/

API for determining gender from first name:
https://genderize.io/

API wrapper:
https://github.com/SteelPangolin/genderize
