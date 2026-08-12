#  Crime Record Management System (CRMS)

A **Database Management System (DBMS) project** designed to efficiently manage and organize crime-related information, including criminal records, cases, complaints, officers, and investigation details.

## Live Demo

🔗 View Live Project
https://crimerecordmanagementsystem-dbms.onrender.com/


##  Overview

The **Crime Record Management System (CRMS)** provides a centralized database for storing and managing crime records. It allows authorized users to add, update, delete, and retrieve information related to crimes, criminals, police officers, complaints, and cases.

The project demonstrates the practical implementation of **DBMS concepts, SQL queries, relational databases, and CRUD operations**.


##  Features



##  Main Modules

### 1. Criminal Management

Stores information about criminals, including their personal details and criminal history.

### 2. Crime & Case Management

Maintains details about registered crimes, cases, crime types, dates, locations, and case status.

### 3. Complaint Management

Stores complaints filed by citizens and associates them with relevant cases.

### 4. Police Officer Management

Maintains police officer details and their involvement in investigations.

### 5. Investigation Management

Links officers, criminals, and cases to keep track of investigations.

##  Technologies Used

* **Database:** MySQL / Oracle
* **Language:** SQL
* **Concepts:** DBMS, RDBMS, CRUD Operations, Joins, Constraints, Relationships
* **Tools:** MySQL Workbench / Oracle SQL Developer

> Replace the database/tool names above with the exact technologies used in your project.

##  Database Concepts Implemented

The project demonstrates several important DBMS concepts:

* Relational Database Design
* Primary Keys
* Foreign Keys
* Unique & NOT NULL Constraints
* Entity Relationships
* Normalization
* SQL Queries
* Joins
* Aggregate Functions
* Subqueries
* Views
* Stored Procedures
* Functions
* Triggers

##  Database Structure

The system consists of multiple interconnected tables such as:

```text
Criminal
    ↓
Crime / Case
    ↓
Complaint
    ↓
Investigation
    ↓
Police Officer
```

The relationships between these entities help maintain consistency and enable efficient retrieval of crime-related information.

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/crime-record-management-system.git
```

### 2. Open the Project

Open the SQL files using your preferred database management tool such as:

* MySQL Workbench
* Oracle SQL Developer

### 3. Create the Database

Run the database creation/schema SQL file.

```sql
CREATE DATABASE CRMS;
```

> If you are using Oracle, create the required schema/tables according to the provided SQL files instead.

### 4. Create Tables

Execute the table creation scripts to create all required tables and relationships.

### 5. Insert Sample Data

Run the provided INSERT queries to populate the database with sample records.

### 6. Execute Queries

Run the provided SQL queries to perform operations such as:

```sql
SELECT * FROM Criminal;
```

You can then perform searching, updating, deleting, joining, and other database operations.

## 📁 Project Structure

```text
Crime-Record-Management-System/
│
├── README.md
│
├── database/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   └── queries.sql
│
├── procedures/
│   ├── procedures.sql
│   ├── functions.sql
│   └── triggers.sql
│
└── screenshots/
    └── database-output.png
```

> Modify the folder structure according to the actual files in your repository.

##  Objectives

* To design a structured relational database for crime records.
* To reduce manual management of crime-related information.
* To provide efficient storage and retrieval of records.
* To demonstrate relationships between different entities.
* To implement DBMS concepts through a real-world application.
* To improve data consistency and accessibility.

##  Future Enhancements

* Add a web-based user interface.
* Implement user authentication and role-based access.
* Add advanced crime analytics and dashboards.
* Implement automated report generation.
* Add crime-location mapping using GIS.
* Introduce advanced search and filtering.
* Deploy the system as a cloud-based application.

## Author

**Mahek Chaurasia**

Computer Science Engineering Student

---

