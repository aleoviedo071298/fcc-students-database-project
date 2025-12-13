# Students Database Bash Project

This project demonstrates how to build, populate, and query a relational PostgreSQL database using Bash scripts and CSV files.

It was created as part of a relational database learning path and focuses on real-world database concepts such as normalization, foreign keys, and automated data insertion.

---

## 📌 Features

- Relational database design with multiple tables
- One-to-many and many-to-many relationships
- Primary keys and foreign keys
- Bash script to populate the database from CSV files
- Bash script to run analytical SQL queries
- Full PostgreSQL database dump included

---

## 🛠️ Technologies Used

- Bash
- PostgreSQL
- SQL (JOINs, GROUP BY, HAVING, subqueries)
- CSV files for data input

---

## 📂 Project Structure

students-database-bash/
├── insert_data.sh # Populates the database using CSV files
├── student_info.sh # Runs SQL queries and prints results
├── students.sql # Full PostgreSQL database dump
├── courses.csv # Courses and majors data
├── students.csv # Students data
└── README.md

---

## ▶️ How to Run

### 1. Restore the database
```bash
psql -U freecodecamp < students.sql
2. Populate the database
bash
Copiar código
./insert_data.sh
3. Run queries
bash
Copiar código
./student_info.sh
📊 Example Queries Included
Students with a 4.0 GPA

Average GPA calculations

Courses with only one student enrolled

Majors with no students

Filtering with conditions, patterns, and ordering

🎯 Learning Goals
Practice relational database modeling

Understand and use foreign keys

Automate database tasks with Bash

Write non-trivial SQL queries

Work with real data input formats

📎 Notes
This project is intended for learning and demonstration purposes.
The database structure and scripts are designed to be simple, clear, and reproducible.

👤 Author
Alejandro Oviedo
