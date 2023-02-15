# Joins

## Intro

1. Please use [db-fiddle](https://db-fiddle.com) to complete this exercise and hand in your work.
2. Joins are very common in SQL work and a developer must be proficient in it.

## Instructions

1. Create these 3 tables below with their respective columns (data types are up to you):
  - User
    - id
    - username
    - password
    - employeeId (foreign key)
  - Employee
    - id
    - companyId (foreign key)
    - jobTitle
    - salary
  - Company
    - id
    - name
    - registrationNumber
    - country
2. Now create 1 company with 3 employees and their respective user accounts by inserting data into the tables. You may enter whatever data you like that makes sense.
3. Now create a query that left joins and selects every column across all 3 tables to display all the data you inserted earlier.

