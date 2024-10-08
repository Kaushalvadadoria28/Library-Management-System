# TDD for Library Management System
 
A simple Library Management System implemented in Python, designed to perform basic operations such as adding books, borrowing books, returning books, and viewing available books. This project follows Test-Driven Development (TDD) principles and emphasizes clean, maintainable code.

## Features

- Add Books: Add new books to the library with details like ISBN, title, author, and publication year.
- Borrow Books: Borrow a book from the library if it is available.
- Return Books: Return a borrowed book and update its availability status.
- View Available Books: View a list of all available books in the library.

# Getting Started

## Prerequisites

- Python 3.x installed on your machine
- Git for version control

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/Kaushalvadadoria28/TDD-for-Library-Management-System.git
   cd TDD-for-Library-Management-System
```

2. Create and activate a virtual environment:
```bash
   python -m venv venv
   venv\Scripts\activate
```
  
3. Install the required dependencies:
```bash
   pip install -r requirements.txt
```
# Usage

## Running the Application

The main application is implemented in library.py. To use the system, you can run your own scripts or use a Python interactive shell to interact with the Library and Book classes.

## Running Tests

This project uses unittest for testing. To run the tests and ensure everything is working correctly, use:
```bash
   python -m unittest test_library.py
```

## Test Results
After running the tests, you should see a output like this:

![Screenshot (403)](https://github.com/user-attachments/assets/65c7b249-db20-4faf-bd39-11ead1980216)


# Project Structure

- library.py: Contains the main implementation of the Library Management System.
- test_library.py: Contains unit tests for the system's functionalities.

# Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new feature branch (git checkout -b feature/YourFeature).
3. Commit your changes (git commit -m 'Add YourFeature').
4. Push to the branch (git push origin feature/YourFeature).
5. Open a pull request.

# License
This project is open-source and available under the MIT License.
