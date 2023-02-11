# Expense-Reimbursement-System-API
The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.

## Skills Used:
Servlets, Java, JDBC, PostgreSQL, Postman, DBeaver

## Overview:
1. Create a Java Maven project in intellij
2. import the following dependencies from mvnrepository and put into pom.xml file:
- postgreSQL
- logback-classic
- Java.servlet-API 
- Junit
- Jackson-core 
- Jackson-databind
3. Create a controller layer, entity layer, service layer, and Data layer for employee and ticket
4. Make employees either manager or regular employee
5. Allow Manager ability to set ticket status as authorized for reimbursement or denied for reimbursement
6. Allow employees to put in ticket amount
7. Create a DbConfig.properties file and put in appropriate variables for connection to database
8. Open DBeaver, create a new database from JDBC url and put in appropriate credentials
9. Open Postman and create a new collection
10. Use HTTP methods on employee and ticket entities to ensure that Expense Reimbursement System API is working correctly
