# awesome-interview-questions
lists of technical interview questions


# Programming Languages/Frameworks/Platforms

## javascript
 What is javascript? - JavaScript is a language. 


## jquery
What is jquery?
 jQuery is a library built with JavaScript to help JavaScript programmers who are doing common web tasks.
 jQuery is a framework of JavaScript.
 
 ## SQL 
 How to find third or nth maximum salary from salary table?
 
select min(employeeid)  from  employees where employeeid in (select top 2 EmployeeID from employees order by EmployeeID desc)

