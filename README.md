Exercise 1: Basic Subquery Understanding

Objective: Understand the concept of subqueries and practice using them in a basic scenario.

Scenario:You have two tables in your PostgreSQL database: **employees** and **departments**.

1.  **employees** table:
    
    *   Columns: id (integer), name (text), department\_id (integer), salary (numeric)
        
2.  **departments** table:
    
    *   Columns: id (integer), name (text)
        

Tasks:

1.  Write a subquery to find the names of all departments.
    
2.  Write a subquery to find the highest salary among all employees.
    
3.  Write a subquery to find the average salary of employees in the department with the highest average salary.
    

Sample Data:

**employees** table:

| id | name | department\_id | salary |

|----|----------|---------------|---------|

| 1 | John | 1 | 50000 |

| 2 | Alice | 2 | 60000 |

| 3 | Bob | 1 | 45000 |

| 4 | Sarah | 3 | 55000 |

**departments** table:| id | name |
                |----|-----------|
                | 1 | Sales |
                | 2 | Marketing |
                | 3 | Finance |
