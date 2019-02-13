# Georgia-salary-gender-differences
Differences and trends in salaries based on gender at Georgia state institutions

# SUMMARY
Even in our current society with the emphasis on equal opportunity, there still exists a significant gender gap in opportunities and salaries. As a child, I was brought up by my single, working mother. Her challenges in the work environment were always felt at home, and I was inspired by her ability to overcome these difficulties.
More recently, I've been aware of gender discrepancies in educational institutions. Why are educational roles so important? Well the next generation of working citizens are students. If students are in an environment where gender inequality is the norm, this will be carried on to the next generation. 

Here, I analyzed salaries from the Open Georgia database which has information about the salary, type of profession, institution, and year ranging from 2010-2018. I used the genderize API to obtain information on gender based on first name. I found that in general, women employees have lower salaries than their male counterparts, by over 40%. The reason for this is two-fold:

1) The proportion of women in low paying jobs (substitute teacher, 8%) relative to the total number of women in the dataset is significantly higher than the relative proportion of men (5%) in low paying jobs. Whereas the relative proportion of men in high paying jobs (professor, ~1-2%) is significantly higher than the relative proportion of women (<0.5%) in professor jobs.

2) The percent difference between salaries of men and women in the same profession increases as the salary increases (yes, the percent difference!).

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
