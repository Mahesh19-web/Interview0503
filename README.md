# Welcome to Facile Technolab Pvt Ltd
Dear Candidate, 

Before you proceed, please review https://www.faciletechnolab.com an award winning custom software development company focusing on excellence at what we do. Here are LinkedIn profiles of the founders:
https://www.linkedin.com/in/lakhlaniprashant/
https://www.linkedin.com/in/ranmalratiya/

# Practical Test
This practical test will evaluate your technical skills in asp.net mvc. There are evaluations for database design, coding standards, web design/html layouts that you use, overall feature implementation, quality of the code submitted and time taken to complete the assignment.

# Features
1. Employee list with paging
2. Add new employee form with validation.

## Project Setup
- Use asp.net mvc5 web application and Visual studio 2017 or 2019 community version. 
- Use Microsoft Sql Server express database and set connection string in web.config
- Use Entity framework code first with migrations to access database
- Use bootstrap (already setup in the default asp.net mvc5 template) to properly style your UI.
- Do not use javascript/jquery for any feature implementation.

## Database Tables
### Department
1. DepartmentId bigint (PK) (Identity - 1,1)
2. DepartmentName nvarchar(50)

Use seed data to enter following departments:
1. Accounts
2. Finance
3. Sales
4. Information Technology
5. Other

### Employees
1. EmployeeId  bigint (PK) (Identity - 1,1)
2. FirstName nvarchar(50) not null
3. LastName nvarchar(50) not null
4. DepartmentId bigint not null (FK - Deparment.DepartmentId) 
5. JoiningDate smalldatetime not null (Valid date not greater than today)
6. EmploymentType int not null (1=full time, 2= part time, 3=consultant) (Dropdown)
7. Salary float (Number only with 2 decimal places)

Use seed data to create 20 employees.

## Feature 1 - Employee list with paging
1. When I run project, I must be able to go to employee listing page through top navigation
2. when I click employees from top navigation, I must be able to see list of employee with standard paging.
3. I must be able to go next/previous in the grid to see all employees.

## Feature 2 - Add employee
1. Put a link to add employee form in employee list page
2. Clicking on add employee button should navigate to add employee form
3. Use validation summary and validations of asp.net mvc to validate form and show errors
4. Once form is submitted it should validate and return error if validation fails
5. Once form is submitted and data is valid, data should be inserted to employee table through entity frameowrk and page should redirect to employee list page.

#Good luck
