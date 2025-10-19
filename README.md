# College Management System Database Showcase

This repository demonstrates my database management and design skills for a College Management System project.

## Overview
The database manages students, programs, courses, departments, and fees.

## Tables and Purpose
- **students**: stores student information
- **programs**: programs offered by the college
- **departments**: departments for programs
- **courses**: courses offered per program
- **fees**: fee structure for each program

## Relationships
- Students belong to Programs (one-to-many)
- Programs belong to Departments (one-to-many)
- Courses belong to Programs (one-to-many)
- Fees are linked to Programs

## How to Use
1. Clone or download this repository.
2. Open phpMyAdmin (or any MySQL client).
3. Create a database named `college_system`.
4. Import `college_system.sql`.
5. Explore tables and relationships.

## ERD
See `ERD.pdf` for the visual diagram of tables and relationships.

## Screenshots
- See `Optional_Screenshots/` for sample table views.
