# Libraray_Management_System

# 📚 Library Management System (Pure Python)

## 📌 Project Overview
The **Library Management System** is a console-based Python application that allows users to view available books, borrow and return books, and view their borrowing history.  
This project is built using **pure Python** and covers **Data Structures**, **OOP Concepts**, and **Exception Handling** — making it ideal for learning and portfolio purposes.

## 🚀 Features
- 📖 Display available books
- 📥 Borrow books
- 📤 Return books
- 📜 View user borrowing history
- 👨‍💻 Admin can add new books

## 🛠 Technologies & Concepts Used
### **Python Core Concepts**
- **Data Structures**
  - **List** → Store available books
  - **Tuple** → Store immutable book details (title, author)
  - **Set** → Track unique borrowed book titles
  - **Dictionary** → Maintain borrow history of users
- **OOP Concepts**
  - **Class** → `Book`, `Library`, `User`, `Admin`
  - **Inheritance** → `Admin` inherits from `User`
  - **Encapsulation** → Protect internal data where required
  - **Polymorphism** → Different display formats using `__str__` method
- **Exception Handling**
  - `ValueError` → Handle invalid numeric inputs
  - `IndexError` → Handle incorrect book selection
  - `KeyError` → Handle non-existent users

 LibraryManagementSystem
 library.py # Main Python file
 README.md # Project Documentation

## ▶️ How to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/LibraryManagementSystem.git
   
Navigate into the Project
cd LibraryManagementSystem

Run the Application
python library.py

 Example Usage
1. Display Books
2. Borrow Book
3. Return Book
4. View Borrow History
5. Exit
Enter choice: 2
Enter your name: Ganesh
Available Books:
1. Python Basics by John Doe
2. Data Structures by Jane Smith
3. OOP in Python by Alex Brown
Enter book number to borrow: 1
Ganesh borrowed 'Python Basics'









