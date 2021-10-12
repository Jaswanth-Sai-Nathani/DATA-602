# ASSIGNMENT 5
### Week 5
In this week we perform regression analysis on San Francisco Employee Compensation data. We perform various regression on the salaries column to understand how it gets impacted based on the incentives provided to the employees. We perform stats model, sklear ols regression and ridge regression on the dataset

###Data Source
This data is approximately 157 MB and is taken from data.sf for analysis. This is very large file so I am not uploading the file and pasting the link to source.
#### Source Link: https://data.sfgov.org/City-Management-and-Ethics/Employee-Compensation/88g8-5mnd
It contains 678525 rows and 22 columns.

#### Data Description
The San Francisco Controller's Office maintains a database of the salary and benefits paid to City employees since the fiscal year 2013. This dataset contains more than 650k employee records found in San Francisco from 2013 to 2020.

1.Organization Group Code: Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.
2.Job Family Code: Job Family combines similar Jobs into meaningful groups.
3.Job Code: Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.
4.Year Type: Fiscal (July through June) or Calendar (January through December).
5.Year: An accounting period of 12 months. The City and County of San Francisco operate on a fiscal year that begins on July 1 and ends on June 30 the following year. The Fiscal 6.Year ending June 30, 2012, is represented as FY2011-2012.
7.Organization Group: Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.
8.Department Code: Departments are the primary organizational unit used by the City and County of San Francisco. Examples include Recreation and Parks, Public Works, and the Police Department.
9.Department: Departments are the primary organizational unit used by the City and County of San Francisco. Examples include Recreation and Parks, Public Works, and the Police Department.
10.Union Code: Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).
11.Union: Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).
12.Job Family: Job Family combines similar Jobs into meaningful groups.
13.Job: Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.
14.Employee Identifier: Each distinct number in the “Employee Identifier” column represents one employee. These identifying numbers are not meaningful but rather are randomly assigned for the purpose of building this dataset. Employee ID has been included here to allow users to reconstruct the original report. Note that each employee’s identifier will change each time this dataset is updated, so comparisons by employee across multiple versions of the dataset are not possible.
15.Salaries: Normal salaries paid to permanent or temporary City employees.
16.Overtime: Amounts paid to City employees working in excess of 40 hours per week.
17.Other Salaries: Various irregular payments made to City employees including premium pay, incentive pay, or other one-time payments.
18.Total Salary: The sum of all salaries paid to City employees.
19.Retirement: City contributions to employee retirement plans.
20.Health and Dental: City-paid premiums to health and dental insurance plans covering City employees. To protect confidentiality as legally required, pro-rated citywide averages are presented in lieu of employee-specific health and dental benefits.
21.Other Benefits: Mandatory benefits paid on behalf of employees, such as Social Security (FICA and Medicare) contributions, unemployment insurance premiums, and minor discretionary benefits not included in the above categories.
22.Total Benefits: The sum of all benefits paid to City employees.


#### Conclusion
1. When we run Stats model we get a very high R square value which is around 99 percent which depicts high variance. The t values also depicts high interdependencies.
2. The the data is mostly linear, When we analysed the Rsquare values for ridge and sklearn came to be similar
3. The alpha values for Ridge regression only changes from 0.1 and above and the r square value decreases from this point which deteriorates the model prediction.
