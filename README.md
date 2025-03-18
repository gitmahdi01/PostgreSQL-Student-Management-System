# PostgreSQL-Student-Management-System
# Student Management System (PostgreSQL)

This project is a simple **Student Management System** using **PostgreSQL**.

## Features:
✅ Create students and courses  
✅ Enroll students in courses  
✅ Query students and courses  
✅ Use stored procedures for enrollment  

## How to Run:
1. Create a PostgreSQL database:
   ```sh
   createdb student_db
psql -d student_db -f database.sql
psql -d student_db -f seed_data.sql
psql -d student_db -f queries.sql
