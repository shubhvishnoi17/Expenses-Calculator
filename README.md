# Expenses-Calculator💰 Expense Calculator - Java Project
📌 Project Overview
The Expense Calculator is a command-line-based Java application that helps users manage their personal expenses efficiently. It allows users to:

Add new expenses

View all recorded expenses

Calculate the total expense

This project demonstrates core Java programming principles and Object-Oriented Programming (OOP) concepts like Encapsulation, Inheritance, Polymorphism, Abstraction, and Interfaces.

🔧 Technologies Used
Java (JDK 8 or above)

IDE: VS Code / IntelliJ / Eclipse (any preferred)

No external libraries used

🧠 OOP Concepts Implemented
Concept	Implementation
Class & Object	User, Expense, and ExpenseItem
Inheritance	Expense inherits from User
Encapsulation	Private fields in ExpenseItem
Abstraction	ExpenseOperations interface
Polymorphism	Method overriding and interface implementation
Constructor Overloading	Used in constructors for creating users and expense entries
Static Keyword	Used for auto-incrementing user ID
This Keyword	Used for differentiating between instance and parameter variables

📂 Project Structure
bash
Copy
Edit
ExpenseCalculator/
│
├── ExpenseCalculatorApp.java      # Main application
├── User.java                      # Parent class
├── Expense.java                   # Expense logic & inheritance
├── ExpenseItem.java               # Single expense encapsulation
├── ExpenseOperations.java         # Interface for abstraction
└── README.md                      # Project documentation
💡 Features
🔐 Secure data structure without using arrays

🎯 Input validation for menu, category, amount, and date

📑 Max limit of 10 expenses to demonstrate memory management

📊 Calculate total expenses in real-time

🧵 Smooth user interaction with simple menu-driven logic

🚫 Error Handling using try-catch and validation blocks

📌 How to Run
Install Java: Ensure JDK is installed and environment variable is set.

Clone Repo:

bash
Copy
Edit
git clone https://github.com/yourusername/ExpenseCalculator.git
Compile the code:

bash
Copy
Edit
javac ExpenseCalculatorApp.java
Run the app:

bash
Copy
Edit
java ExpenseCalculatorApp
✅ Sample Usage
mathematica
Copy
Edit
Welcome to Expense Calculator!
Enter your name: Shubh

---- Menu ----
1. Add Expense
2. View Expenses
3. Calculate Total
4. Exit
Enter choice: 1
Enter category: Food
Enter amount: 250
Enter date: 2025-06-10
Expense added successfully.
🛡 Validation & Error Handling
✔ Category and Date cannot be blank

✔ Amount cannot be negative or zero

✔ Expense limit is capped at 10

✔ Menu options outside 1-4 are rejected

✔ Scanner safely closed at the end

📚 Learning Outcome
This project helped demonstrate a real-world application of:

Java Fundamentals

Object-Oriented Design

Clean Code Practices

Data Validation & Exception Handling

Menu-driven CLI-based application development

📌 Author
👤 Shubh Vishno
