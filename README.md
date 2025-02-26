# PIBLIO
# Library Management System

## Description

PIBLIO is a **C++** console-based library management system that allows students and library employees to manage book borrowings, returns, and searches efficiently.

## Features

- **Library Employee Mode:**

  - Secure access with a password.
  - Add new books to the library.
  - Save book records to a file.

- **Student Mode:**

  - Borrow books by providing necessary details.
  - Return borrowed books.
  - Search for books by title, author, or category.

## Technologies Used

- **C++** for core logic.
- **File handling** to store books and borrowing data.

## File Structure

- `livres.txt` - Stores book details.
- `emprunts.txt` - Stores borrowing records.

## How to Run

1. Compile the C++ code using g++:
   ```sh
   g++ -o piblio piblio.cpp
   ```
2. Run the program:
   ```sh
   ./piblio
   ```
3. Follow the prompts to either add books (as an employee) or borrow/search for books (as a student).

## Future Improvements

- Implement a graphical user interface (GUI).
- Add a database for better storage management.
- Implement fine calculations for overdue books.

## Author

**Abdelouahab Kribaa**

