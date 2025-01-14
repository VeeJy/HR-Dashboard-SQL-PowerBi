![image alt](https://github.com/user-attachments/assets/d4a7d667-6e1f-44c9-ba6e-ec2089bc1b8f)

![image](https://github.com/user-attachments/assets/7be3858c-3a9e-4694-80dd-75f1ee61203c)



# Data Used

**Data** - HR Data with over 22000 rows from the year 2000 to 2020.

**Data Cleaning & Analysis** - SQL Server, Jupyter Notebook

**Data Visualization** - PowerBI

# Questions

1. What is the gender breakdown of employees in the company?
2. ﻿﻿﻿What is the race/ethnicity breakdown of employees in the company?
3. ﻿﻿﻿What is the age distribution of employees in the company?
4. ﻿﻿﻿How many employees work at headquarters versus remote locations?
5. ﻿﻿﻿What is the average length of employment for employees who have been terminated?
6. ﻿﻿﻿How does the gender distribution vary across departments and job titles?
7. ﻿﻿﻿What is the distribution of job titles across the company?
8. ﻿﻿﻿Which department has the highest turnover rate?
9. ﻿﻿﻿What is the distribution of employees across locations by state?
10. ﻿﻿﻿﻿How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

# Summary of Findings

- ﻿﻿There are more male employees
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 22 years old and the oldest is 59 years old. ﻿﻿5 age groups were created (21-28, 29-36, 37-44, 45-52, 53-60). A large number of employees were between 
  37-44 followed by 29-36 while the smallest group was 53-60.﻿﻿
- A large number of employees work at the headquarters versus remotely.﻿﻿
- The average length of employment for terminated employees is around 10 years.
- The gender distribution across departments is fairly balanced but there are generally more male than female employees.
- The Marketing department has the highest turnover rate followed by Business Development. The least turn over rate are in the Auditing, Legal and Training departments.
- A large number of employees come from the state of Ohio.﻿﻿
- The net change in employees has increased over the years.
- The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Marketing having the lowest.

# Limitations

- Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
