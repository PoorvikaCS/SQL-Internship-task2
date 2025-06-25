 SQL Internship - Task 2: Data Insertion and Handling Nulls

Objective
This task focuses on practicing core DML operations like INSERT, UPDATE, and DELETE. It also demonstrates handling NULL values and default constraints in SQL.

 Table Created
Table Name:Employees

| Column Name | Type     | Description                     |
|-------------|----------|---------------------------------|
| emp_id      | INTEGER  | Primary key                     |
| name        | TEXT     | Not null                        |
| age         | INTEGER  | Optional                        |
| department  | TEXT     | Default value 'General'         |
| salary      | REAL     | Salary value                    |
| bonus       | REAL     | Can be NULL                     |

Operations Performed
- Created `Employees` table with constraints
- Inserted 3 records (Anu, Praju , Poorvi)
- Used `NULL` and `DEFAULT` values
- Updated `bonus` using `UPDATE`
- Deleted Praju using `DELETE`
- Displayed final table using `SELECT *`

Output Preview

| emp_id | name    | age | department | salary | bonus |
|--------|---------|-----|------------|--------|-------|
| 1      | Anu     | 30  | HR         | 50000  | 5000  |
| 3      | Poorvi  |     | IT         | 60000  | 2000  |


