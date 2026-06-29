# Library Management System

A desktop Library Management System built with Python and PyQt5.

## Features

- Add and manage books
- Manage book categories, authors, and publishers
- Track lending and returning of books
- Generate Excel reports from library data
- Add and manage users with login and profile updates
- Apply multiple UI themes

## Technologies

- Python
- PyQt5
- SQLite database
- Qt Designer for UI layout
- CSS-style application themes

## Installation

1. Install Python 3.
2. Install dependencies:
   ```bash
   pip install PyQt5
   ```
3. Run the application:
   ```bash
   python index.py
   ```

## Project Structure

- `index.py` - application entry point
- `library.ui`, `library2.ui`, `login.ui` - Qt Designer UI files
- `db.sql` - database schema and sample data
- `icons_rc.py`, `icons.qrc` - bundled icons
- `themes/` - CSS theme files

## Notes

This project is a complete desktop application for managing a library and its users. It includes book inventory management, user authentication, and reporting tools.
