# hr-employee-data-analysis
HR Employee Cleaning, Analysis, and Visualization (SQL and PowerBI)

# 👋 Introduction
This project analyzes an HR employee dataset with over 22,000 rows from 2000 to 2020. I used MySQL Workbench for data cleaning and analysis, and PowerBI to visualize the data. Follow along to see how I completed this project from beginning to end.

![image](https://github.com/amyquach/hr-employee-data-analysis/assets/143021553/16fc07cd-e2f2-4125-a41f-8c5eaa129974)
![image](https://github.com/amyquach/hr-employee-data-analysis/assets/143021553/7ae46e1f-6916-43ef-81d1-121d0274e182)

# 🔎 Purpose
Project 1 uses SQL and PowerBI to conduct a comprehensive analysis of a sample HR employee dataset. By extracting, cleaning, and transforming the data through SQL queries, this lays the foundation in-depth insights for the company. The final PowerBI report empowers HR professionals and leaders to visualize key HR metrics, predict attrition, and make data-driven decisions. This project aims to improve employee satisfaction, optimize for organizational performance, and showcases how we can leverage data for a more efficient and engaged workforce.

This project is organized into three distinct phases: Data Cleaning, Data Analysis, and Data Visualization. Follow along for a detailed, step-by-step breakdown of each process, while gaining a comprehensive view of my approach to leveraging data for HR insights.

# ❓ Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

# 📖 Summary of Findings

- There are more male employees than other genders.
- For race/ethnicity, White employees are the most dominant while Native Hawaiian or Other Pacific Islander/American Indian are the least dominant.
- Out of the 5 age groups created (18-24, 25-34, 35-44, 45-54, 55-64), a large number of employees are in the 25-34 age group, with 35-44 closely following in second. The least amount of employees belongs to age group is 55-64.
- About 75% of employees work at headquarters, while the rest work remotely.
- The average length of employment for terminated employees is around 7-8 years.
- Gender distribution is fairly balanced amongst Male and Female employees, however, there is a significantly smaller number of Non-Conforming employees.
- The Marketing and Business Development Departments have the highest turnover rate, while the Auditing and Legal Departments have the lowest turnover rate.
- A large number of employees are from Ohio, specifically Cleveland.
- The net change of employees has increased over the years based on hire and term dates.
- The average tenure for Engineering, Services, Sales, Auditing, Accounting, Research and Development, and Marketing is 8 years, while the lowest is Product Management at 6 years.

# ❌ Weaknesses and Limitations

- 967 records were excluded due to incorrect birth years resulting in negative ages.
    - For a real dataset, the best practice would be to work with the data provider to update the birth years, then run a data quality check to minimize the amount of data excluded.
- Only ages 18 and up were used in the data analysis.
- 1599 records were excluded due to incorrect termination dates. These were placed far into the future. Because this is a data quality issue, in a real dataset, the ideal situation would be to work with the data provider to correct and update the incorrect values.
    - To strengthen data quality in future analyses, it is important to define data quality standards and develop comprehensive data cleaning procedures.
