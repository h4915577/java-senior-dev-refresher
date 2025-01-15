1. What is composite key ?
2. Index - Primary and others.
3. Outer join vs Inner Join
4. Relationship of jpa vs hibernate
5. JPA - Explain how to implement @ManyToMany, @ManyToOne and @OneToOne annotations.
6. How to use composite key in JPA ?
7. Which object is locked in Synchronized Map ?
8. Which object is locked in Synchronized Map ?

9. 2) Write an SQL Query to return employee Name and Department name where Employee Table have EMpID, Name , dept, salary and Department table have dept_id and dept_name
3) Wrtire an SQL query to return Emp Name and Department name , Also return the Employees who are not assgined to any department yet
4) What is LEFT Outer Join
5) Write a Query to return the department name  , max min and average salary of that department

5 Again in depth question on the DB isolation levels in which scenario to use what. Lots of why
and how

10. Self Join
SQL Question on Self Join
Question : Give first name, last name of employee and their manager whose country is India
SQL : 
SELECT 

    e.first_name, e.last_name,

    m.first_name, m.last_name

FROM

    employees e

        INNER JOIN

    employees m 

	ON m.employee_id = e.manager_id

WHERE e.country = 'India'
https://www.sqltutorial.org/sql-self-join/
10. 
