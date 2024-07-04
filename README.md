# Library Management System

This is a web-based application designed to manage a library's inventory of books, including tracking book rentals, sales, and availability. The system provides an intuitive user interface for both library staff and users.

## Features

- **Dashboard**: Overview of total books, rental and sales statistics.
- **Book Listing**: View available, rented, and sold books.
- **Add New Book**: Interface for adding new books to the library inventory.
- **Book Details**: Information about individual books, including title, author, price, and status.

## Screenshots

### Dashboard

The dashboard provides a quick summary of the library's performance, including the number of available, sold, and rented books, as well as the profits from sales and rentals.

### Book Listing

This page lists all the books in the library's inventory. Each book card displays:
- Title
- Author
- Price
- Number of pages
- Status (Available, Rented, Sold)

### Add New Book

The form to add a new book includes the following fields:
- Title
- Author
- Book cover photo
- Author photo
- Number of pages
- Price
- Rental price per day
- Rental period
- Total rental cost
- Status (Available, Rented, Sold)
- Category (Novel, Art, History, Horror, etc.)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/devachref/library-management.git
    ```
2. Start the development server:
    ```bash
    python manage.py runserver
    ```

## Usage

- Navigate to `http://localhost:8000` in your web browser.
- Use the dashboard to get an overview of the library's performance.
- Use the book listing page to browse and manage books.
- Use the "Add New Book" form to add new books to the inventory.


## Project Link

[Task Manager GitHub Repository](https://github.com/devachref/library-management.git)
