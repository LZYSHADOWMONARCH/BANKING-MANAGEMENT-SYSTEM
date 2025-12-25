# Banking Management System (Java)

A **Java-based Banking Management System** desktop application that simulates core ATM and banking operations using **Java Swing** and **MySQL database connectivity**.

This project is designed for **academic / learning purposes** and demonstrates real-world banking workflows like account creation, login, deposits, withdrawals, balance enquiry, and more.

---

## 📁 Project Structure

project_structure:
  banking-management-system:
    .idea: "IntelliJ IDEA configuration files"

    Libraries:
      mysql-connector-java.jar: "MySQL JDBC driver"
      jcalendar-1.4.jar: "Date picker library"

    out: "Compiled output files"

    src:
      banking:
        management:
          BalanceEnquiry.java: "Check account balance"
          Conn.java: "Database connection class"
          Deposit.java: "Deposit money"
          FastCash.java: "Quick withdrawal feature"
          Login.java: "User login screen"
          Main_Class.java: "Main dashboard / ATM menu"
          Mini.java: "Mini statement"
          Pin.java: "Change PIN"
          Signup.java: "Account signup (Step 1)"
          Signup2.java: "Account signup (Step 2)"
          Signup3.java: "Account signup (Step 3)"
          Withdrawl.java: "Withdraw money"

    icon:
      atm2.png: "ATM UI image"
      backbg.png: "Background image"
      bank.png: "Bank logo"

    .gitignore: "Git ignored files"
    README.md: "Project documentation"



---

## 🚀 Features

- 🔐 Secure Login using PIN
- 📝 Multi-step Account Signup
- 💰 Deposit Money
- 💸 Withdraw Money
- ⚡ Fast Cash Withdrawal
- 📊 Balance Enquiry
- 🧾 Mini Statement
- 🔁 Change ATM PIN
- 🗄️ MySQL Database Integration
- 🖥️ User-friendly GUI (Java Swing)

---

## 🛠️ Technologies Used

- **Java (JDK 8+)**
- **Java Swing & AWT**
- **MySQL**
- **JDBC**
- **IntelliJ IDEA**

---

## 🔗 External Libraries Required

| Library | Purpose |
|------|--------|
| mysql-connector-java.jar | MySQL database connectivity |
| jcalendar-1.4.jar | Date selection in signup forms |

👉 Make sure both JAR files are added to **Project Libraries**.

---

## ⚙️ Database Setup

1. Install and start **MySQL Server**
2. Create a database (example):
   ```sql
   CREATE DATABASE banksystem;
   USE banksystem;
Create required tables (signup, login, transactions, etc.)

Update database credentials inside:

java
Copy code
Conn.java
▶️ How to Run the Project
Open project in IntelliJ IDEA

Add required JAR files to libraries

Ensure MySQL server is running

Run:

java
Copy code
Login.java
Use the GUI to perform banking operations

🧑‍💻 Entry Point
java
Copy code
Login.java
This is the first screen shown to the user.

📌 Notes
Keep all images inside the icon folder

Do not rename package banking.management

Database connection must be correct to avoid runtime errors

Designed for desktop use only

🎓 Academic Use
This project is ideal for:

Java Mini Project

Semester Project

ATM Simulation System

👨‍💻 Authors
Sujal Gupta and Mohd Taqi
Java Banking Management System Project

