# Smart College Placement Portal

A role-based College Placement Portal developed using **Java, JDBC, and MySQL** to streamline the campus recruitment process. The application allows students to apply for jobs, recruiters to manage job postings, and administrators to oversee the complete placement workflow.

---

## 📌 Features

### 👨‍🎓 Student Module
- Student Registration & Login
- Update Profile
- View Eligible Jobs
- Apply for Jobs
- Track Application Status
- View Placement Results

### 🏢 Recruiter Module
- Recruiter Login
- Company Registration
- Create Job Openings
- View Eligible Candidates
- Schedule Interviews
- Update Selection Status

### 👨‍💼 Admin Module
- Manage Students
- Manage Companies
- Manage Job Postings
- Monitor Applications
- Generate Placement Reports
- View Dashboard Statistics

---

## 🛠️ Tech Stack

| Technology | Description |
|------------|-------------|
| Java | Core Application Development |
| JDBC | Database Connectivity |
| MySQL | Relational Database |
| SQL | CRUD Operations & Queries |
| OOP | Object-Oriented Programming |
| Collections Framework | Data Management |
| Git & GitHub | Version Control |

---

## 📂 Project Structure

```
Smart-College-Placement-Portal/
│
├── src/
│   ├── model/
│   ├── dao/
│   ├── service/
│   ├── util/
│   ├── exception/
│   └── main/
│
├── database/
│   ├── schema.sql
│   └── sample_data.sql
│
├── screenshots/
│
├── README.md
└── pom.xml (Optional)
```

---

## 🗄️ Database Tables

- Students
- Recruiters
- Companies
- Jobs
- Applications
- Interviews
- PlacementResults

---

## 💻 OOP Concepts Used

- Classes & Objects
- Encapsulation
- Inheritance
- Abstraction
- Interfaces
- Polymorphism
- Exception Handling
- Packages

---

## 📊 SQL Concepts Used

- Primary Key
- Foreign Key
- Constraints
- Joins
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- CRUD Operations

---

## 📚 DSA Concepts Used

- ArrayList
- HashMap
- Sorting
- Searching
- Collections Framework

---

## 🔄 Workflow

1. Student registers and logs in.
2. Recruiter creates company profile and posts job openings.
3. System checks student eligibility based on predefined criteria.
4. Eligible students apply for jobs.
5. Recruiters review applications and schedule interviews.
6. Admin manages placement activities and generates reports.
7. Final placement status is updated.

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Smart-College-Placement-Portal.git
```

### Open Project

Open the project in IntelliJ IDEA or Eclipse.

### Configure Database

1. Install MySQL.
2. Create a database:

```sql
CREATE DATABASE placement_portal;
```

3. Run the `schema.sql` file.

4. Update database credentials in:

```java
DBConnection.java
```

Example:

```java
private static final String URL = "jdbc:mysql://localhost:3306/placement_portal";
private static final String USER = "root";
private static final String PASSWORD = "your_password";
```

### Run the Project

Execute:

```
Main.java
```

---

## 📈 Future Enhancements

- Resume Upload
- Email Notifications
- Password Encryption
- Admin Analytics Dashboard
- Company-wise Statistics
- Interview Feedback Module
- PDF Offer Letter Generation

---

## 🎯 Learning Outcomes

- Java Programming
- JDBC Connectivity
- MySQL Database Design
- SQL Query Writing
- Object-Oriented Programming
- Collections Framework
- CRUD Operations
- Layered Architecture (DAO-Service-Model)
- Basic Software Design Principles

---

## 👨‍💻 Author

**Tejas Sainadh Kumar Kabotula**

- GitHub: https://github.com/TejasKabotula
- LinkedIn: https://linkedin.com/in/your-profile

---

## 📜 License

This project is created for educational and learning purposes.
