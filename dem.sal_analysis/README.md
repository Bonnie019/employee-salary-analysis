# Employee Demographics & Salary Analysis
A python_based data analysis project exploring employee records, departmental headcounts and payroll allocations.
## Project workflow
**Data extraction(MySQL)**: Began by using an 'INNER JOIN' in MySQL workbench to merge data from the 'employee_salary' and 'employee_demographics'tables into a unified data set.
**Export**: Saved the joined tables as a '.CSV' file in the local 'dem.sal.csv' file.
**Analysis and visualization**: Processed the CSV using pandas and generated the final distribution charts using seaborn in VSCode.

## Summary of insights
* **Demograpics**: Evaluates age distribution across the company to find the oldest and youngest employees.
*  **Payroll breakdown**: Groups employee salaries to calculate cumulative spending per department.
* **Data Visualization**: Includes a seaborn bar chart showing departmental budget distributions.
## Visual chart result
The script automatically generates this departmental chart layout:
![Total salary by Department Graph](total_salary_chart.png)
