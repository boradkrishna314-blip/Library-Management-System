# Library Management System (C++)

A console-based **Library Management System** built in C++ using Object-Oriented Programming (OOP) concepts (`Library` class and array of objects). The application allows users to record book inventory and student issue details and display all stored entries cleanly in the terminal.

## Features

- **Add Book & Issue Details:** Store Book ID, Book Name, Author Name, Issued Student Name, Book Price, and Total Pages (supports up to 20 records per session).
- **Multi-Word Input Support:** Uses `cin.getline()` with a `$` delimiter so book titles, author names, and student names containing spaces are captured accurately.
- **Display Records:** View all entered book and student issue records in a structured console output.
- **Menu-Driven Loop:** Continuous `while` and `switch` navigation with input validation until the user chooses to exit.

## Project Structure

```text
Library-Management-System/
├── main.cpp             # Main C++ source code (Library class & menu logic)
├── README.md            # Project documentation
└── .gitignore           # Git ignore rules for compiled binaries and IDE files
