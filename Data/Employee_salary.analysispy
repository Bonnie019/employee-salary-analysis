import pandas as pd 
import matplotlib.pyplot as plt
import seaborn as sns
df = pd.read_csv('employee_salary.csv')
average_salary = df['salary'].mean()
highest_salary = df['salary'].max()
total_salary = df['salary'].sum()

print ("The average salary is:")
print (average_salary)
print ("The highest salary is:")
print (highest_salary)
print ("The total salary output is:")
print (total_salary)
plt.figure(figsize=(10, 6))
plot = sns.histplot(df['salary'], bins=10, kde=True)
plt.title('Salary Distribution')
plt.xlabel('Salary Amount',fontsize=12)
plt.ylabel('No. of Employees',fontsize=12)
plt.show()
