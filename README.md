# SQL Injection

## Overview
- SQL Injection (SQLi) is a security vulnerability that occurs when an attacker is able to manipulate a website's database query by inserting harmful SQL code into an input field. This allows the attacker to access, modify, or delete data from the database, potentially gaining unauthorized access to sensitive information such as user credentials, private data, or the database structure.
- SQL Injection usually happens when a website doesn't properly validate or sanitize user inputs before using them in SQL queries.

## How SQL Injection Works
- User Input: A website takes input from the user and directly inserts it into an SQL query.
- Malicious Input: An attacker enters harmful SQL code into an input field.
- Modified Query: The website executes the altered SQL query, causing it to perform unintended actions.
- Impact: Depending on the type of SQL Injection, the attacker could:
- -Extract sensitive data from the database.
- -Change or remove records.
- -Bypass authentication and gain unauthorized access.
  
## Key Concepts
- Understanding SQL queries.
- Exploiting injection points.
- Preventing SQL Injection attacks.

## Labs
| **S.No** | **Lab Name**                                                                               |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 1        | [Lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data.](./SQL_Injection/README.md)                                               |
| 2        | [Lab: SQL injection vulnerability allowing login bypass](./Cross_Site_Scripting/README.md)                           |
| 3        | [Lab: SQL injection attack, querying the database type and version on Oracle](./CSRF/README.md)                                    |
| 4        | [Lab: SQL injection attack, querying the database type and version on MySQL and Microsoft](./Clickjacking/README.md)                                                 |
| 5        | [Lab: SQL injection attack, listing the database contents on non-Oracle databases](./Authentication/README.md)                                            |
| 6        | [Lab: SQL injection attack, listing the database contents on Oracle](./Path_Traversal/README.md)                                             |
  
