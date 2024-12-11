Library Management System

A desktop-based Library Management System built using Java Swing and MySQL, with JDBC for database connectivity. This application is designed to streamline library operations such as managing books, tracking borrow and return transactions, and handling user accounts.

Features

Book Management: Add, update, delete, and search for books.

User Management: Add and manage library users (students and staff).

Borrow and Return Records: Track the borrowing and returning of books.

Authentication: Secure login system for administrators and users.

Technologies Used

Programming Language: Java

Framework: Java Swing for GUI

Database: MySQL

Connectivity: JDBC (Java Database Connectivity)

IDE: Eclipse

Installation

Prerequisites

Java JDK installed on your system.

MySQL installed and configured.

Eclipse IDE for Java Developers.

Steps to Set Up

Clone the repository:

git clone https://github.com/yourusername/library-management-system.git

Open Eclipse and create a new Java project:

Launch Eclipse.

Click on File > New > Java Project.

Name the project (e.g., LibraryManagementSystem) and click Finish.

Add the source files to the project:

Copy the contents of the src folder from the cloned repository.

Paste the files into the src folder of your newly created project in Eclipse.

Configure the MySQL database:

Create a database in MySQL named library_management.

Execute the SQL script provided in the database folder to set up tables and sample data.

Update database credentials:

Open the DatabaseConnection.java file in the project.

Update the URL, username, and password variables to match your MySQL configuration.

Run the project:

Right-click on the library.java file.

Select Run As > Java Application.
