🏦 Java Bank Management System
📌 Overview

The Java Bank Management System is a console-based application developed using Core Java that simulates basic banking operations. This project demonstrates the use of Object-Oriented Programming (OOP) concepts, JDBC, and MySQL for managing bank accounts and transactions.

🚀 Features

Create new bank accounts

Deposit money

Withdraw money

Check account balance

View account details

Secure database connectivity using JDBC

Input validation and exception handling

🛠️ Technologies Used

Programming Language: Java

Database: MySQL

Connectivity: JDBC

IDE: Eclipse / VS Code

Version Control: Git & GitHub

🧱 Project Structure
BankManagementSystem
│
├── src
│   ├── BankMain.java
│   ├── Account.java
│   ├── BankService.java
│   ├── DatabaseConnection.java
│
├── lib
│   └── mysql-connector.jar
│
└── README.md

⚙️ How to Run the Project

Clone the repository:

git clone https://github.com/sachinyb/bank-management-system.git


Open the project in Eclipse or VS Code

Add MySQL Connector JAR to the project build path

Create database and table in MySQL:

CREATE DATABASE bankdb;

USE bankdb;

CREATE TABLE accounts (
    account_number INT PRIMARY KEY,
    name VARCHAR(100),
    balance DOUBLE
);


Update database credentials in DatabaseConnection.java

Run BankMain.java

📂 Database Connectivity

Uses JDBC for connecting Java application to MySQL

Performs CRUD operations on bank account records

📚 Concepts Implemented

Object-Oriented Programming (OOP)

Encapsulation and Abstraction

JDBC and SQL Queries

Exception Handling

Console-based User Interaction

🎯 Learning Outcomes

Hands-on experience with Java and database integration

Understanding of real-world banking operations

Improved problem-solving and debugging skills

🔗 GitHub Repository

👉 https://github.com/sachinyb/bank-management-system

👨‍💻 Author

Sachin

GitHub: https://github.com/sachinyb

LinkedIn:https://www.linkedin.com/in/sachin-y-b-703588352

⭐ If you like this project

Give it a ⭐ on GitHub!
