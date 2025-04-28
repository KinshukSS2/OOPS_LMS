# OOPS_LMS
Library Management System-BY GROUP 18
Members:Pratibha,Tejdeep,Amit,Kinshuk,Mohit,Devansh

Project Overview
The Library Management System (LMS) is designed to facilitate the management of library operations. It helps in maintaining the library's book inventory, managing members, and tracking issued and returned books. The system includes functionalities like adding new books, issuing books to members, returning books, and searching for books by title, author, or ISBN.

Features
Add New Books: Allows the librarian to add new books to the system.

Issue Books: Enables issuing books to registered members.

Return Books: Members can return borrowed books and update the inventory.

Search Books: Books can be searched by title, author, or ISBN.

View Transaction History: The system keeps a record of all book transactions.

Manage Members: Register new members and manage their details.

Installation
Requirements
[Insert programming language or platform you're using, e.g., Java, C++, etc.]

Database (e.g., MySQL, SQLite) for managing data

Required libraries or frameworks (if applicable)

Steps to Install
Clone the repository:

bash
Copy
Edit
git clone [repository_url]
Navigate to the project directory:

bash
Copy
Edit
cd Library-Management-System
Set up the database:

Create a new database (e.g., MySQL or SQLite).

Run the provided SQL script to create the required tables.

Compile and run the application:

Follow the instructions for your chosen language (e.g., using javac and java commands for Java).

Usage
After compiling and running the program, interact with the system via the command line or graphical user interface (if implemented).

You can add books, issue books to members, search for books, and manage transactions.

Database Structure
The database consists of the following main tables:

Books: Contains book details (ID, title, author, ISBN, quantity).

Members: Stores information about library members (ID, name, contact details).

Transactions: Keeps a log of all book issues and returns (book ID, member ID, issue date, return date).
