## Question 1
You would use the command `psql my_db`. 
Use `\c` to show a list of databases.
Use `\d` to show a list of tables in a database.


## Question 2
Select SUM(price)
from table;

## Question 3 

#EmployeeID Join
| employee_id | department_id | name | salary | location |
|:--:|:--:|:--:|:--:|:--:|
| 2 | 1 | Jon | 40000 | null |
| 7 | 1 | Linda | 50000 | null |
| 12 | 2 | Ashley | 15000 | null |
| 1 | 0 | Mike | 80000 | null |
| null | 1 | null | null | NY |
| null | 2 | null | null | SF |
| null | 3 | null | null |Austin |

#DepartmentID Join
| employee_id | department_id | name | salary | location |
|:--:|:--:|:--:|:--:| :--:|
| 2 | 1 | Jon | 40000 | NY |
| 7 | 1 | Linda | 50000 | NY |
| 12 | 2 | Ashley | 15000 | SF |
| 1 | 0 | Mike | 80000 | null |
| null | 3 | null | null |Austin |