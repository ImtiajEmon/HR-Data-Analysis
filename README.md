# HR-Data-Analysis
EDA &amp; Power BI Dashboard on HR Dataset

---
### Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Data Description](#data-description)

### Project Overview
This project involves the creation of a comprehensive Power BI dashboard for analyzing Human Resources (HR) data. The dashboard provides insights into key HR metrics such as employee demographics, performance, attrition, and more. The goal of this dashboard is to help HR professionals make informed decisions based on data-driven insights.

### Project Structure
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Power BI Dashboard
- Drawing Conclusion

### Data Description
[Dataset](https://www.kaggle.com/datasets/imtiajemon/hr-dataset/data)

#### Summary:
This is a dataset about almost 1500 employees. They works in different departments with different job roles. There are 60% male employee and 40% female employee. Most of them are married. However, around 16% of them have left their job.

#### Column Descriptions:
- `EmpID`: Employee ID of each employee.
- `Age`: Age of each employee.
- `AgeGroup`: Age group.
- `Attrition`: Whether the employee left his/her job or not.
- `BusinessTravel`: Describe the employee's business travel frequency.
- `Department`: Which department the employee currently working.
- `DistanceFromHome`: Distance of office from home.
- `EducationField`: Employee's education field.
- `EnvironmentSatisfaction`: Satisfaction level on employee's work environment.
- `Gender`: Gender of employees.
- `JobLevel`: Employee's job level in their office.
- `JobRole`: Role of employee's.
- `JobSatisfaction`: Job satisfaction level of employees.
- `MaritalStatus`: Marital status of employees.
- `MonthlyIncome`: Employee's income per month.
- `Over18`: Indicate the specific employee is 18+ or not.
- `OverTime`: Whether the employee do overtime or not.
- `PercentSalaryHike`: Salary hike in percentage.
- `PerformanceRating`: Rating on employee's performance.
- `TotalWorkingYears`: Total working year of employees.
- `YearsAtCompany`: Working year at current company.
- `YearsInCurrentRole`: Working year at current role.
- `YearsSinceLastPromotion`: Number of year since the last promotion.
- `YearsWithCurrManager`: Number of year with current manager.

### Tools
- Python - Pandas, Matplotlib, Seaborn
- Power BI

### Exploratory Data Analysis (EDA)
[Exploratory Data Analysis]()

### Power BI Dashboard

![image](https://github.com/user-attachments/assets/80c1341f-64c5-4c67-af4f-b030750aa451)

### Results/Findings
 - Employees of this company travel rarely
 - Employees who are travel rarely and travel frequently are most likely to leave the job.
 - Most of the non-traveller employee don't want to leave their job.
- There are 3 departments.
- Employee of`Reasearch & Development` and `Sales` department are more likely to leave the job.
- Employee from `Life Science` department are more likely to quit their job.
- Company has more number of male emplyee. Hence the number of attrition is little more for male employees.
- `Laboratory Technician` and `Sales Executive` are most likely to quit their job.
- `Research Director`s and `Manager`s are not trending to leave their jobs.
- Most of the employees are married.
- Unmarried employess are most likely to leave the job.
- Employeees in age of 25 to 40 are more likely to leave their job.
- There are no outliers in the age data.
- Higher the monthly income, lower the attrition count.
- Average income per month is 6500.23$.
- But there are lots of outliers in `MonthlyIncome` column.

### Recommendations
**1. Address Travel-Related Issues**
- Flexible Travel Policies: Since employees who travel rarely or frequently are more likely to leave, consider implementing more flexible travel policies. Offer remote work 
  options or reduce the need for frequent travel by leveraging virtual meetings.
- Support for Frequent Travelers: Provide additional support for employees who frequently travel, such as travel allowances, flexible work hours, or wellness programs to 
  reduce travel-related stress.
  
**2. Focus on Department-Specific Retention Strategies**
- Research & Development and Sales Departments: Employees in these departments are more likely to leave. Implement department-specific engagement programs, provide clear 
  career growth paths, and offer incentives to retain talent.
- Life Sciences Department: Since employees in this department are also likely to quit, consider conducting exit interviews to understand their concerns and address any 
  department-specific issues.
  
**3. Targeted Support for High-Risk Job Roles**
- Laboratory Technicians and Sales Executives: These roles show higher attrition rates. Offer additional training, career development opportunities, and recognition programs 
  to improve job satisfaction and retention in these positions.
- Retention Programs for High-Risk Roles: Consider implementing targeted retention programs for roles with higher turnover, focusing on mentorship, professional growth, and 
  work-life balance.
  
**4. Gender-Specific Initiatives**
- Support for Male Employees: Since the company has more male employees and a slightly higher attrition rate among them, consider gender-specific initiatives such as work-  
  life balance programs, wellness initiatives, and recognition programs to improve retention.
  
**5. Focus on Age-Specific Engagement**
- Retention Strategies for Ages 25-40: Employees aged 25 to 40 are more likely to leave. Implement retention strategies that appeal to this age group, such as career 
  development opportunities, leadership training, and flexible working arrangements.
  
**6. Review Compensation Strategies**
- Address Income Disparities: Since higher monthly income is associated with lower attrition, review and adjust compensation strategies to ensure competitive pay, especially 
  for roles with high turnover. Consider implementing performance-based bonuses or salary increases.
- Outlier Analysis for Monthly Income: Given the presence of outliers in the Monthly Income data, conduct a thorough analysis to ensure pay equity and fairness. Address any 
  significant disparities to prevent dissatisfaction among employees.
  
**7. Conduct Regular Engagement Surveys**
- Monitor Employee Satisfaction: Regularly conduct employee engagement surveys to monitor job satisfaction across departments, roles, and demographics. Use the insights to 
  proactively address potential issues before they lead to attrition.
