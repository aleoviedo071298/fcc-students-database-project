Perfecto, vamos a dejarlo **limpio, prolijo y 100% copy-paste**, sin secciones de más ni ruido visual.
Este queda **bien estético en GitHub** y profesional.

---

```md
# Students Database Bash Project

Bash scripts to populate and query a relational PostgreSQL students database using CSV files.

---

## Overview

This project demonstrates how to automate the creation, population, and querying of a PostgreSQL database using Bash scripting.  
It focuses on relational database concepts such as primary keys, foreign keys, and many-to-many relationships.

---

## Technologies

- Bash
- PostgreSQL
- SQL
- CSV

---

## Project Structure

```

students-database-bash/
├── insert_data.sh
├── student_info.sh
├── students.sql
├── courses.csv
├── students.csv
└── README.md

````

---

## How to Use

### 1. Restore the database
```bash
psql -U freecodecamp < students.sql
````

### 2. Populate the database

```bash
./insert_data.sh
```

### 3. Run queries

```bash
./student_info.sh
```

---

## What This Project Covers

* Relational database design
* Primary and foreign keys
* Many-to-many relationships
* Automated data insertion from CSV files
* SQL queries with JOIN, GROUP BY, and HAVING

---

## Author

Alejandro Oviedo

```

---
