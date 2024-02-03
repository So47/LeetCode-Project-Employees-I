# Write your MySQL query statement below
Select P.project_id, ROUND(AVG(E.experience_years),2) As average_years
From Project P 
Inner JOIN Employee E
ON P.employee_id = E.employee_id
GROUP BY P.project_id
    
