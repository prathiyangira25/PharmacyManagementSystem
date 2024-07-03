# Pharmacy Management System
# Overview
This repository contains the codebase for a Pharmacy Management System implemented in Java using Oracle SQL*Plus for database management. The system is designed to streamline operations within a pharmacy environment, handling inventory, prescriptions, and customer management.

# Features
Database Management: All database operations, including table creations, data manipulations, and stored procedures, are implemented using Oracle SQL*Plus.

JDBC Connectivity: The system connects to the Oracle database using JDBC (Java Database Connectivity), ensuring secure and efficient communication between the frontend and backend.

User Interface: The frontend of the application is developed using Java Swing frames, providing a user-friendly interface for pharmacy staff to manage daily operations.

# Installation
To run the Pharmacy Management System locally, follow these steps:

Setup Oracle Database: Ensure Oracle SQL*Plus is installed and configured on your machine. Create the necessary tables and stored procedures as outlined in the SQL scripts provided.

Configure JDBC Connection: Update the JDBC connection settings (Connection.java or equivalent) in the Java codebase to point to your Oracle database instance.

Import Project: Open the project in NetBeans IDE or your preferred Java IDE. Import the source files and configure the project settings accordingly.

Build and Run: Build the project and run the main application file (Main.java or equivalent) to launch the Pharmacy Management System.

# Files Included
src/: Contains all Java source files for the application.
requirements.txt: Includes SQL scripts for creating tables, procedures, and initializing the database.
README.md: This file providing an overview of the project and installation instructions.
# Usage
Use the application to manage pharmacy inventory, handle prescriptions, and manage customer information through the intuitive Swing-based user interface.
Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome to enhance functionality, improve user experience, or fix bugs.
