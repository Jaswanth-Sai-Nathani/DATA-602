## Assignment 3 
This assignment we are going to do expolaratory data analysis on the San Francisco employee salary compensation.
This data is approximately 157 MB and is taken from data.sf for analysis. This is very large file so I am not uploading the file and pasting the link to source.
#### Source Link: https://data.sfgov.org/City-Management-and-Ethics/Employee-Compensation/88g8-5mnd
It contains 678525 rows and 22 columns.

#### Content
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

#### Target:
Total Compensation: The sum of all salaries and benefits paid to City employees.

Note:
Rows may have zero dollar amounts:
Zero-dollar amounts could be present for various reasons, for example, a separated employee receiving a one-time payout of accrued vacation hours but no other salary or fringe benefits during the period. In this case, the employee would have a non-zero amount in “Other Salaries” but zeroes in “Salaries”, “Overtime”, and all fringe benefits categories.

Adjustments to employee's pay can result in negative dollar amounts:
Negative amounts generally represent adjustments made to employees' pay that was associated with a different time period, expenditure category, or job than the original payment.
An example of this would be an employee who was erroneously overpaid at the end of Fiscal Year 2013 with an adjustment to correct the mistake not occurring until the beginning of Fiscal Year 2014. If this employee received no other payments in Fiscal Year 2014 for the same department and job, the report would show only this adjustment for the employee as a negative amount.



