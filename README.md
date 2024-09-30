# Employee Attrition Insights and Retention Strategies

## Table of Contents

- [Business Problem](#business-problem)
- [Rationale for the Project](#rationale-for-the-project)
- [Aim of the Project](#aim-of-the-project)
- [Data Description](#data-description)
- [Tech Stack](#tech-stack)
- [Project Scope](#project-scope)
- [Analysis and Insights](#analysis-and-insights)
- [Recommendations](#recommendations)

## Business Problem
McCurr Consultancy, a global MNC, seeks to reduce the costs associated with employee retention by focusing on those most at risk of leaving the organization. By analyzing employee data, McCurr aims to identify key factors influencing employee attrition and use these insights to develop targeted strategies that retain top talent.

## Rationale for the Project
McCurr invests heavily in employee retention initiatives. However, to optimize costs, the Head of People Operations proposes targeting only employees at risk of leaving the organization. By understanding patterns in employee attrition, McCurr can tailor its retention efforts, ensuring resources are used more effectively and efficiently.

## Aim of the Project
The goal of this project is to identify and analyze the factors that contribute to employee attrition using available data. The insights will allow McCurr to pinpoint employees at risk and provide actionable recommendations. These insights will be visualized in a Power BI dashboard for easy interpretation by management.

## Data Description
- EmployeeNumber - Employee Identifier
- Attrition - Did the employee attrite?
- Age - The age of the employee
- BusinessTravel - Travel commitments for the job
- DailyRate - Data description not available
- Department - Employee Department
- DistanceFromHome - Distance from work to home (in km)
- Education - 1-Below College, 2-College, 3-Bachelor, 4-Master,5-Doctor
- EducationField - Field of Education
- EmployeeCount - Employee Count in a row
- EnvironmentSatisfaction - 1-Low, 2-Medium, 3-High, 4-Very High
- Gender - Employee's gender
- HourlyRate - Data description not available
- JobInvolvement - 1-Low, 2-Medium, 3-High, 4-Very High
- JobLevel - Level of job (1 to 5)
- JobRole - Job Roles
- JobSatisfaction - 1-Low, 2-Medium, 3-High, 4-Very High
- MaritalStatus - Marital Status
- MonthlyIncome - Monthly Salary
- MonthlyRate - Data description not available
- NumCompaniesWorked - Number of companies worked at
- Over18 - Over 18 years of age?
- OverTime - Overtime?
- PercentSalaryHike - The percentage increase in salary last year
- PerformanceRating - 1-Low, 2-Good, 3-Excellent, 4-Outstanding
- RelationshipSatisfaction - 1-Low, 2-Medium, 3-High, 4-Very High
- StandardHours - Standard Hours
- StockOptionLevel - Stock Option Level
- TotalWorkingYears - Total years worked
- TrainingTimesLastYear - Number of training attended last year
- WorkLifeBalance - 1-Low, 2-Good, 3-Excellent, 4-Outstanding
- YearsAtCompany - Years at Company
- YearsInCurrentRole - Years in the current role
- YearsSinceLastPromotion - Years since the last promotion
- YearsWithCurrManager - Years with the current manager

## Tech Stack
This project was developed using the following tools:
- Power BI: For creating interactive visualizations and dashboards.
- Power Query: For data transformation and preparation within Power BI.
- DAX (Data Analysis Expressions): For performing data analysis and creating custom calculations within Power BI.

## Project Scope
The scope of the project includes:
1. Data Importation: Import dataset from source into Power BI
2. Data Analysis: Performing exploratory data analysis (EDA) using Power Query to clean and transform the dataset.
3. Data Visualization: Creating interactive Power BI dashboards to visualize patterns in employee attrition and identify at-risk employees.
4. Insights Generation: Using DAX calculations to generate insights into key factors such as job satisfaction, work-life balance, distance from home, and overtime, and how these influence attrition.
5. Recommendations: Providing actionable recommendations to management based on the insights, aimed at reducing employee turnover by focusing on high-risk employees.

## Analysis and Insights
The report comprises 5 pages:
1. Overview/Summary
2. Demographics & Job Roles
3. Satisfaction & Work-life Balance
4. Performance & Compensation
5. Recommendations

You can interact with the report here...

### Summary
This page focuses on the key factors driving attrition and highlights the main retention risks to management.
- We see that the Company has a total of 2,940 employees, 474 of those left the company during the period in consideration. This gives an Attrition rate of 16%.
- We see that tenure is a significant factor, with 364 employees out of 474 (~77%) leaving within the first 10 years.
- Attrition is concentrated in Research & Development, particularly in roles such as Laboratory Technicians, Sales Executives, and research Scientists, which are essential to the company's operations.
- Job satisfaction and Commuting distance also contribute to turnover, with 132 (40%) employees that left having long commutes to work.
- Alarmingly, McCurr is losing it's top performers (84%), with some of them working overtime, suggesting possible burn out.

These are the key areas where targeted interventions can help retain the company's best talents and reduce attrition.

### Demographics & Job Roles
Here, we'll have a closer look into who- which employee demographics and job roles are most impacted by attrition.
- We see that Attrition is higher among male employees (63%) and single employees (50%), especially among the 26-35 age group, who may be seeking better oppportunities.
- Also, attrition is predominant in junior/entry-level roles (Job Role 1) at 60%, indicating thet junior staff may lack engagement or growth paths.

Retention strategies focusing on career development and engagement for these groups can reduce turnover.

### Satisfaction and Work-Life Balance
This page explores how job satisfaction, work-life balance, and the work-environment affect attrition.
- Job satisfaction is a key factor, with 28% (132) of employees that left expressing dissatisfaction with their jobs.
- Interestingly, 254 of the 474 employees that left had an excellent work-life balance, meaning other factors like job satisfaction and overtime (worked by 53.5% of leavers) may be driving attrition.
- The work environment also played a role, with 144 employees who left expressing dissatisfaction with it.

### Performance and Compensation
- The majority of employees who left earned between 1k-5k per month, indicating that compensation could be a factor.
- 84% of those who left are excellent performers, meaning the Company is losing it's top talents.
- Employees who received the lowest salary hikes were more likely to leave, suggesting that financial recognition may be inadequate.

## Recommendations

Focus Retention Efforts on Employees with 1-10 Years of Tenure:

- 77% of attrition comes from employees who have been with the company for not more than 10 years. To retain talent, management should enhance career development, offer growth opportunities, and focus on engaging employees in their early years at the company.

Improve Job Satisfaction, especially in Critical Roles:

- 28% of employees who left were dissatisfied with their jobs, and the company is losing top performers (84%), particularly in Research & Development and key job roles like Laboratory Technicians and Sales Executives. Management should address job satisfaction through role-specific interventions, such as career growth, recognition, and feedback.


Address the Impact of Overtime and Distance from Work:

- 53% of employees who left worked overtime, and 40% lived far from work, indicating possible burnout and commuting issues. Offering flexible working options and reducing excessive overtime could improve retention and work-life balance, particularly for those affected by long commutes.
