# Data Manipulation


## Introduction:
This set of tasks involves the manipulation of data using MySQL database. The primary objective of these tasks is to serve as a guide for understanding the various aspects of data manipulation within MySQL tables. Through these tasks, I have gained insights in areas such as replacing data, modifying data, merging data, and data cleaning.

## Problem statement:
1. replace the department ‘communication’ with ‘stakeholders’ and show the result of the replacement done.

2. Update the ‘name’ column ensuring that the values are all in UPPER CASE.

3. Run a query that will show the employer's name and DOE in one column as the Employer’s brief.

4. Run a query that will remove leading spaces from the name column If exists.

## Result/Discussion:

The above snapshot clearly shows the changes made to the 'Department', and the command used for this task is as follows:

_UPDATE table_name_

_SET department = 'stakeholders'_

_WHERE department = 'communication';_


![](Upper_Case.png)

the snapshot above shows the column with updated values converted to uppercase, and the SQL command used to achieve this, is as follows:

_SELECT Employee_ID,_

_upper( Name) AS Name from employee_info;_



![](Upper_Case.png)


The snapshot above shows the merged data of the employee's name and Date of Entry (DOE). The syntax use to achieve this, is as follows:

_SELECT CONCAT(name, ' ', DOE)_

_AS "Employee’s brief" FROM employee_info;_

## Conclusion:

These tasks have provided me a hands-on experience in data manipulation within a MySQL database. The primary objective was to get familiarized with various data manipulation commands, including data replacement, text modification, data merging, and data cleaning.

The first snapshot demonstrated how to efficiently replace data within the 'Department' column using an SQL UPDATE command. The second snapshot showcased the transformation of text data to uppercase, ensuring uniformity in the 'name' column.

Lastly, the third snapshot illustrated the merging of employer names and Date of Entry (DOE) into a single column named "Employee’s brief”.

These tasks collectively highlight the versatility of SQL in managing and enhancing data within a MySQL database, ultimately contributing to more effective data management and analysis.
