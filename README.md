# BankUML

A Java-based banking system simulation that implements core banking operations and account management using UML design principles. The project includes features such as user authentication, multiple account types, and transaction handling. Designed as a study resource for UML-driven software modeling and Java application development.

---

## 📌 Features

- **User Authentication** — Login system for secure access
- **Account Management** — Create and manage different types of accounts
- **Transaction Handling** — Deposit, withdraw, and transfer between accounts
- **UML-Driven Architecture** — Classes and relationships based on UML diagrams
- **OOP Principles** — Inheritance, encapsulation, abstraction, and polymorphism

## 📊 Diagram
<img width="424" height="310" alt="image" src="https://github.com/user-attachments/assets/f04c95b4-fc87-419e-88b7-ab136cf45139" />

This diagram demonstrates the classes within the BankUml project template. Inheritance relationships are shown with solid line arrows, whilst implied relationships are shown with dashed line arrows. This is only a reference for the template, and you are free to change the application architecture as you see fit!

## 🚀 How to Run

Make sure you have the following installed:

- Java
- Maven (if Lombok is missing or not working correctly)

1. Clone the repository:

```bash
git clone https://github.com/M-PERSIC/BankUml.git
cd BankUml
```

2. Compile the code:

```bash
javac -cp "libs/*" bank/*.java 
```

3. Run the program:

```bash
# Linux/MAC
java -cp ".:libs/*" bank.Main
# Windows
java -cp ".;libs/*" bank.Main
```

To redownload the Lombok jar:

```bash
mvn dependency:copy-dependencies -DoutputDirectory=./libs
```

---
