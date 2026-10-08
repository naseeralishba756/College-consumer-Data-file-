# College Database - MySQL Practice

## Overview
Practiced MySQL queries on `college` database - consumer table with 8 records.
This project demonstrates accuracy in data handling - key skill for Branch Services Officer (BSO) roles.

## What I Did
- Added ID column as AUTO_INCREMENT PRIMARY KEY
- Updated consumer age from 17 to 20 using WHERE clause
- Handled SQL_SAFE_UPDATES for secure updates
- Verified changes with SELECT queries

## Queries Executed
```sql
SET SQL_SAFE_UPDATES = 0;
UPDATE consumer SET Age = 20 WHERE Age = 17;
SELECT * FROM consumer WHERE Age < 17 AND Gender = 'Female';
SELECT * FROM consumer ORDER BY Age ASC;# College-consumer-Data-file-