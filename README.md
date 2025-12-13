# 🎓 Students Database Bash Project

Bash scripts to populate and query a relational PostgreSQL students database using CSV files.

---

## 📖 Overview

This project automates the creation, population, and querying of a PostgreSQL database using Bash.  
It demonstrates core relational database concepts such as primary keys, foreign keys, and many-to-many relationships.

---

## 🛠️ Technologies

- 🐧 Bash
- 🐘 PostgreSQL
- 🧠 SQL
- 📄 CSV

---

## 📂 Project Structure

students-database-bash/
├── insert_data.sh
├── student_info.sh
├── students.sql
├── courses.csv
├── students.csv
└── README.md

yaml
Copiar código

---

## ▶️ How to Use

### 1️⃣ Restore the database
```bash
psql -U freecodecamp < students.sql
2️⃣ Populate the database
bash
Copiar código
./insert_data.sh
3️⃣ Run queries
bash
Copiar código
./student_info.sh
✅ What This Project Covers
🔗 Relational database design

🗝️ Primary and foreign keys

🔄 Many-to-many relationships

⚙️ Automated data insertion from CSV files

📊 SQL queries with JOIN, GROUP BY, and HAVING

👤 Author
Alejandro Oviedo****
