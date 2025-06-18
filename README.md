# online_banking_system.java
This is a **Bank Management System** desktop application built using **Java** in **NetBeans IDE**. It uses **SQLite** as the backend database and GUI is designed using **NetBeans GUI Builder** (Swing-based). The system allows basic banking functionalities like account creation, deposit, withdrawal, balance check, and fund transfer.

---

## ✅ Features

- Create New Bank Accounts
- Deposit & Withdraw Money
- Transfer Funds Between Accounts
- Check Account Balance
- View Transaction History
- Clean and interactive GUI using NetBeans Designer

---

## 🛠️ Technologies Used

| Technology       | Description                              |
|------------------|------------------------------------------|
| Java             | Programming Language                     |
| NetBeans         | IDE used for development (with GUI Builder) |
| SQLite           | Backend Database                         |
| JDBC             | Java Database Connectivity                |
| JTattoo          | Modern GUI Look & Feel                   |
| rs2xml.jar       | Display ResultSet in JTable              |

---

## 📁 Project Structure

```
📦 Project Root
 ┣ 📂 lib/
 ┃ ┣ 📄 sqlitejdbc-v056.jar
 ┃ ┣ 📄 rs2xml.jar
 ┃ ┗ 📄 JTattoo-1.6.11.jar
 ┣ 📂 database/
 ┃ ┗ 📄 bank.sqlite
 ┣ 📂 src/
 ┃ ┗ 📄 (Java source files created in NetBeans)
 ┗ 📄 README.md
```

---

## ▶️ How to Run

1. **Clone or Download** this Repository

2. **Open Project in NetBeans IDE**

3. Right-click on the project > **Properties** > Add the following libraries in "Libraries":
   - `sqlitejdbc-v056.jar`
   - `rs2xml.jar`
   - `JTattoo-1.6.11.jar`

4. **Make sure `bank.sqlite` database file is in correct path**

5. **Run the Project** (Right-click on Main file > Run)

---

## 🧠 Learning Outcomes

- GUI building using NetBeans (Drag & Drop)
- Java Database (JDBC) Programming
- CRUD operations with SQLite
- Using JAR files in Java projects
- Project modularization and OOP
