# Librarymanagement
# Database Setup and Schema Design

## 📌 Objective

To learn and implement the process of designing a relational database by:
- Creating databases and tables
- Defining relationships using primary and foreign keys
- Generating an Entity-Relationship (ER) diagram

---

## 🧰 Tools Used

- MySQL Workbench *(used in this project)*
- pgAdmin / SQLiteStudio *(alternatives)*

---

## 📁 Librarymanagement

| File Name       | Description                                   |
|----------------|-----------------------------------------------|
| `library.sql`   | SQL script to create schema and relationships |
| `ER_Diagram.png`| ER diagram visualizing the database structure |

---

## Steps Followed (Mini Guide)

1. **Choose a Domain**:  
   Selected the **Library Management System** domain for schema design.

2. **Identify Entities and Relationships**:  
   - Entities: `Author`, `Book`, `Member`, `Loan`  
   - Relationships:  
     - One author can write many books  
     - One member can borrow many books (through `Loan`)  
     - One loan links one member to one book  

3. **Create Tables Using SQL**:  
   Used `CREATE TABLE` statements in MySQL to define the schema with appropriate data types.

4. **Define Primary and Foreign Keys**:  
   - Primary Keys: Uniquely identify each record in a table  
   - Foreign Keys: Enforce referential integrity between tables  

---

## 📚 Overview of the Schema

- The schema includes **4 main tables**:
  - `Author`
  - `Book`
  - `Member`
  - `Loan`
- Proper normalization is followed to remove redundancy.
- Relationships are clearly defined with foreign key constraints.

---

## ✅ Outcome

- A **well-structured relational schema** using SQL
- A corresponding **ER diagram** that visually represents all entities and relationships

---

## 📎 How to Use

1. Open `MySQL Workbench`
2. Run the script `library.sql` to create the database schema
3. Use **Forward Engineering** to generate the ER diagram from the script or  
   **Reverse Engineering** from an existing database to view the diagram
4. Open `ER_Diagram.png` to review the final ER structure

---

## 🙋‍♀️ Author

**Name**: Sahana K C  
---

