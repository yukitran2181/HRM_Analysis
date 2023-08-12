# HRM_Analysis
## A. About the Data Source
Please see the data source in here: 
https://docs.google.com/spreadsheets/d/13Fq1KJJb-AZf2AwrFZPLFvw_KQor8yu787Xgb_jOh3o/edit?usp=drive_web&ouid=104331042475265706671

The HR department has assembled data on almost 15,000 employees who left the company. They used information from exit interviews, performance reviews, and employee records.

Take a look at our dataset, we have 10 attributes in detail as:

- satisfaction_level: It is employee satisfaction point, which ranges from 0-1.
- last_evaluation: It is evaluated performance by the employer, which also ranges from 0-1.
- number_projects: How many of projects assigned to an employee?
- average_monthly_hours: How many hours in average an employee worked in a month?
- time_spent_company: time_spent_company means employee experience. The number of years spent by an employee in the company.
- work_accident: Whether an employee has had a work accident or not.
- promotion_last_5years: Whether an employee has had a promotion in the last 5 years or not.
- Department: Employee's working department/division.
- Salary: Salary level of the employee such as low, medium and high.
- left: Whether the employee has left the company or not.

## B. Project Plan & Hypothesis
1. Data cleaning: removing duplicates, correcting null values, and missing values, fixing typos, and converting data types properly. ( with patience and care!!! This step is very important to have accurate data findings!)

2. Export data to SQL database finding relationships in employee metrics

3. Our hypothesis is that a low satisfaction rate made employee quit their jobs, we have to first test if this was a high conversion rate between low satisfaction and turnover rate. Then find out which metrics are highly correlated with a low satisfaction score.

4. We are going to look at relationships between employee satisfaction vs salary, satisfaction conversion rate to turnover rate, and how their promotion or project involvement impacted satisfaction ratings.

5. Export data set to visualizations in Tableau, we need to create storytelling visualizations.

## C. Recommendations
These recommendations were implemented from SQL's results and data visualization via PBI
1. Focus on increasing promotion system  within these departments: HR, Accounting, Technical, Support and Sales. It is observed that  departments have a very high churn rate (18%) yet they have very few promotions or even no promotions in the department. The reasoning behind this strategy is that with employees,develop a clear promotion system to enable internal growth in these departments, it is important for employees to see a clear path of position advancement within the company

2. In addition, these 5 departments shared a similar pattern, with people with low salaries having a tendency to quit their jobs at a rate of ~20-22%, while those with medium salaries also had a high churn rate of ~14-17%. Therefore, company should reconsider about salary policy compared with the work load.

3. Most people with a high churn rate are those with a satisfaction rate of only 0.2 or 0.4. The company can conduct regular performance reviews and use the above milestones to warn and pay more attention to these employees. In addition, it is necessary to conduct more in-depth demographic studies on the churn and non-churn groups, as well as the reasons they decided to quit.
