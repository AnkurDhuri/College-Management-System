# College Management System

A **Java Swing** desktop application for managing college student records, using **MySQL** as the backend. It supports two user roles:

- **Admin** – Can add, update, search, and delete student records.
- **User** – Can search student records.

---

##  Project Features

- Intuitive GUI built with **Java Swing**.
- CRUD operations on `acollege` table (fields: `Id`, `Name`, `Class`).
- Admin interface for full record management.
- User interface for searching student records.
- JDBC-based connection to a MySQL database.

---

##  Prerequisites

Ensure the following are installed and configured:

- **Java JDK** (version 8 or higher)
- **MySQL Server**
- **MySQL Connector/J** (JDBC driver)
- **Maven** (if using the Maven project structure)

---

##  Setup Instructions

### 1. Database Setup

Run the following SQL in your MySQL console or client:
```sql
CREATE DATABASE college;
USE college;

CREATE TABLE acollege (
  Id INT PRIMARY KEY,
  Name VARCHAR(100),
  `Class` VARCHAR(50)
);
-- Insert sample data
INSERT INTO acollege (Id, Name, Class) VALUES
(1, 'John Doe', 'B.Sc Computer Science'),
(2, 'Jane Smith', 'B.A Economics'),
(3, 'Michael Brown', 'B.Com Accounting');
```

### 2. Run the Application
Compile the project in your IDE (e.g., NetBeans, IntelliJ IDEA, Eclipse).
Run the main class to start the application.

### 3. Screenshots
<img width="746" height="501" alt="Welcome" src="https://github.com/user-attachments/assets/c73179b1-a158-47ba-ad9a-b6742d788f0c" />
<img width="750" height="493" alt="Login" src="https://github.com/user-attachments/assets/51c27164-4a3a-4341-a9d5-ff8f717127b5" />
<img width="745" height="497" alt="Operations" src="https://github.com/user-attachments/assets/512b7760-0963-477d-a651-232e267aaee6" />
<img width="747" height="490" alt="ADD Students" src="https://github.com/user-attachments/assets/67b9ea59-cf42-4261-ad12-6f30f43d3f26" />
<img width="741" height="497" alt="Delete" src="https://github.com/user-attachments/assets/c88435a9-ee7d-46e9-91c5-e661ad5a6b27" />
<img width="747" height="493" alt="Search" src="https://github.com/user-attachments/assets/49885a97-636d-4286-97d3-3f84b2be2179" />
<img width="748" height="492" alt="Update" src="https://github.com/user-attachments/assets/909b34bc-6688-4a5b-b554-3bdb5f8d2b0d" />
<img width="757" height="497" alt="Updateload" src="https://github.com/user-attachments/assets/0f7993e1-ebbf-48a0-b82c-32ca19c79e83" />
<img width="747" height="492" alt="UpdateStud" src="https://github.com/user-attachments/assets/4398a601-e1c2-44df-86b9-f5d6c0c2a7c5" />
