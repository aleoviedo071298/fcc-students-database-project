# Students Database Bash Project

Bash scripts to populate and query a relational PostgreSQL students database from CSV
files, built for freeCodeCamp's Relational Database certification.

## Overview

This project automates the creation, population, and querying of a PostgreSQL
database using Bash. It demonstrates core relational database concepts: primary
keys, foreign keys, and many-to-many relationships.

## Tech Stack

- Bash
- PostgreSQL
- SQL
- CSV

## Project Structure

```
students-database-bash/
├── insert_data.sh
├── student_info.sh
├── students.sql
├── courses.csv
├── students.csv
└── README.md
```

## How to Use

1. Restore the database:
   ```bash
   psql -U freecodecamp < students.sql
   ```
2. Populate the database from the CSV files:
   ```bash
   ./insert_data.sh
   ```
3. Run queries:
   ```bash
   ./student_info.sh
   ```

## What This Project Covers

- Relational database design
- Primary and foreign keys
- Many-to-many relationships
- Automated data insertion from CSV files
- SQL queries with `JOIN`, `GROUP BY`, and `HAVING`

## Author

**Alejandro Oviedo**
