# SQL-code
Code practice using LeetCode problems
#176. Second Highest Salary
select max(salary) as SecondHighestSalary
FROM Employee 
where salary <(select max(salary)from Employee);
