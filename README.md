# Discovering Databases: An Easy Start for Beginners

## Project Overview
This project introduces databases, SQL, and Python integration with MySQL through an online bookstore scenario. You will:

- Create a MySQL database.
- Design tables with proper relationships.
- Insert data into tables.
- Query database metadata.
- Use Python to automate database creation.

## Project Structure
```
Intro_to_DB/
├── MySQLServer.py
├── alx_book_store.sql
├── task_2.sql
├── task_3.sql
├── task_4.sql
├── task_5.sql
├── task_6.sql
└── README.md
```

## Prerequisites
- MySQL Server installed and running.
- Python 3.x installed.
- `mysql-connector-python` package:
```bash
pip install mysql-connector-python
```

## Instructions

1. **Create Database**
```bash
python MySQLServer.py
```

2. **Create Tables**
```bash
mysql -u root -p < task_2.sql
```

3. **List Tables**
```bash
mysql -u root -p -D alx_book_store < task_3.sql
```

4. **Describe 'books' Table**
```bash
mysql -u root -p -D alx_book_store < task_4.sql
```

5. **Insert Single Customer**
```bash
mysql -u root -p -D alx_book_store < task_5.sql
```

6. **Insert Multiple Customers**
```bash
mysql -u root -p -D alx_book_store < task_6.sql
```

## Notes & Best Practices
- All SQL keywords are uppercase.
- Python script handles connection and errors safely.
- Foreign keys maintain referential integrity.
- Naming uses consistent snake_case.
- Data is normalized to avoid redundancy.

## Optional Extensions
- JOIN queries for orders/customers/books.
- Python CRUD scripts.
- Use as backend for Flask/Django app.
