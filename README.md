# Database Repository

Welcome to the **Database** repository! This repository contains MySQL database scripts and practice exercises to enhance understanding of database concepts.

## 📌 About This Repository
This repository is dedicated to **basic MySQL database coding practice**. It includes fundamental SQL queries, table creation scripts, data manipulation, and other essential database operations. Whether you're a beginner or looking to refresh your SQL skills, this repository provides structured scripts and exercises to help you gain hands-on experience.

## 🚀 Getting Started
To set up and run the scripts, follow these steps:

### 1️⃣ Install MySQL
Ensure you have MySQL installed on your system. You can download it from the official [MySQL website](https://www.mysql.com/downloads/).

### 2️⃣ Clone the Repository
Use the following command to clone the repository to your local machine:
```sh
git clone https://github.com/tanvir-talha058/database.git
```


### 3️⃣ Open MySQL and Create a Database
After installing MySQL, log into MySQL and create a database for practicing:
```sql
CREATE DATABASE practice_db;
USE practice_db;
```

### 4️⃣ Execute SQL Scripts
Run the provided scripts in the correct order to set up and populate the database:
```sh
mysql -u root -p practice_db < create_tables.sql
mysql -u root -p practice_db < insert_data.sql
```

## 🛠 Topics Covered
This repository covers a wide range of SQL topics, including but not limited to:

### 📌 Database Creation & Management
- Creating databases and tables
- Defining primary and foreign keys
- Setting constraints (NOT NULL, UNIQUE, CHECK, DEFAULT)

### 📌 Data Manipulation (CRUD Operations)
- **INSERT** statements to add data
- **SELECT** queries for retrieving data
- **UPDATE** queries to modify existing records
- **DELETE** statements for data removal

### 📌 Advanced Querying
- **Joins** (INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN)
- **Subqueries** for complex queries
- **Aggregate functions** (SUM, COUNT, AVG, MIN, MAX)
- **Grouping & HAVING clause**

### 📌 Performance Optimization
- **Indexing** to speed up queries
- **Stored Procedures** for reusable logic
- **Triggers** for automated actions
- **Views** for simplified querying

## 📢 Contributions
Contributions are welcome! If you have any improvements, suggestions, or additional SQL exercises to share, feel free to fork the repository and submit a pull request. You can also open issues for discussion.

## 📄 License
This repository is licensed under the **MIT License**.

---
Happy Coding! 🎯
