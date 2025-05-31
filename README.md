# Library Management System

## Overview
The Library Management System (LMS) is a console-based application developed in C++ to streamline library operations for both librarians and students. It leverages Object-Oriented Programming (OOP) principles to create a modular and maintainable system. The project uses file handling to persistently store data in text files, addressing inefficiencies in manual library management by simplifying processes, enhancing security, and improving resource management.

## Features
- **User Roles**: Supports two user roles—Librarian and Student—with distinct functionalities.
- **Librarian Features**:
  - Manage books: Add, search, update, delete, and set availability status.
  - Manage students: Register, search, update, delete student profiles, and handle fines.
- **Student Features**:
  - View book catalog, search books, view profile, and manage borrowed books (view/renew).
- **Book Management**:
  - Add, search, update, and display books with details like title, author, ISBN, and availability.
- **Borrowing System**:
  - Borrow books, track due dates, issue dates, and calculate fines for overdue books.
- **Security**:
  - User authentication for login and access control for librarians.
- **Data Persistence**:
  - Stores data in text files (`librarian_data.txt`, `book_data.txt`, `student_data.txt`, `borrowed_book_data.txt`).

## Installation
1. **Prerequisites**:
   - A C++ compiler (e.g., g++ on Windows/Linux/Mac).
   - Windows OS (for `windows.h` and `conio.h` dependencies).

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/Yusra-Munawwar/Library-Management-System.git
   cd Library-Management-System
   ```

3. **Compile the Code**:
   - Use a C++ compiler to compile the main source file (e.g., `main.cpp`):
     ```bash
     g++ main.cpp -o lms
     ```

4. **Run the Application**:
   - Execute the compiled binary:
     ```bash
     ./lms
     ```
   - Ensure the following text files are in the same directory as the executable: `librarian_data.txt`, `book_data.txt`, `student_data.txt`, and `borrowed_book_data.txt`. If they don’t exist, the program will create them.

## Usage
1. **Launch the Application**:
   - Run the program to access the main menu.

2. **Choose Role**:
   - Select your role: Librarian or Student.
   - For Librarian: Log in with credentials or register if new. Use the verification key for access.
   - For Student: Log in with your ID and password or register as a new student.

3. **Librarian Portal**:
   - Manage books: Add, search, update, delete, or set availability.
   - Manage students: Register, search, update, delete profiles, or handle fines.
   - Log out to return to the main menu.

4. **Student Portal**:
   - View book catalog, search for books, view your profile, or manage borrowed books.
   - Log out to return to the main menu.

## Technologies Used
- **Language**: C++
- **Libraries**:
  - Standard libraries: `<iostream>`, `<iomanip>`, `<fstream>`, `<string>`, `<vector>`, `<limits>`, `<algorithm>`, `<ctime>`
  - Windows-specific: `<windows.h>`, `<conio.h>`, `<ios>`
- **Data Storage**: File handling with text files (`librarian_data.txt`, `book_data.txt`, `student_data.txt`, `borrowed_book_data.txt`)

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a pull request on GitHub.

