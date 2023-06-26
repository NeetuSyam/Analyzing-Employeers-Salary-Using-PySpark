# Analyzing-Employeers-Salary-Using-PySpark

 The project's objective is to examine data pertaining to 100,000 000 employees, with an emphasis on EMployseer's Salary in particular. To analyze the data and extract meaningful information using SQL queries, the Pyspark framework will be used in particular. Finally, the Gradient Boosted Tree (GBT) algorithm is trained using Pyspark MLlib to perform Feature Engineering and estimate employer salary.

 ### Results 

<li>The industry with highest income is OIL, second is FINANCE and third is WEB.</li>
For every jobtype, workers with higher degree have a higher income.
The highest paid job is CEO, while the least paid is JANITOR.
For every jobtype, Engineering, Businees and Math are the majors which lead to higher income.
The average income of workers with no experience differs a lot among the jobtype:
CEO has a base average income around 120k$, CFO around 110k\$ while Janitor only 47k$.
Among all jobs, mean, median and mode salary are respectively 116k$, 114k\$ and 108k$. They do not coincide due to the right skeweness of the salary distribution.
