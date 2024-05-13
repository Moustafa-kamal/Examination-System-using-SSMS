# ADV_DB_ITI_Project
# Overview
The Online Examination System is a comprehensive solution for conducting exams online. It includes an automated system for exam generation, answering, correction, and a SQL database to store all relevant data.

# Features
Entity-Relationship Diagram (ERD) & Backup: The ERD diagram for the database schema is provided in the database/ERD directory. Database backup files are stored in the database/backup directory.
Database Dictionary (Documentation): Detailed documentation of the database structure, including tables, columns, and relationships, can be found in the database/documentation directory.
Stored Procedures: The system implements stored procedures for efficient database operations, including:
Select, Insert, Update, and Delete operations on any table.
Exam Generation: Automatically generates randomized exams based on predefined criteria.
Exam Answers: Stores exam answers submitted by examinees.
Exam Correction: Automatically corrects exam answers and provides results.
# System Requirements
Database Management System: MySQL, PostgreSQL, or similar.
Development Environment: Java, .NET, or similar.
Minimum Hardware Requirements:
Processor: Intel Core i3 or equivalent
RAM: 4GB
Storage: 100MB free disk space
# Installation
Clone this repository to your local machine.
Install the necessary database management system.
Execute the SQL scripts provided in the database directory to create the database schema and populate initial data.
Set up the database connection settings in the system configuration file.
Build and deploy the system.
# Usage
Admin Panel: Access the admin panel to manage exams, questions, and users.
Exam Generation: Generate new exams with specified criteria such as duration, difficulty, and subject.
Exam Taking: Examinees can log in and take assigned exams within the specified time frame.
Exam Correction: The system automatically corrects exam answers and provides detailed results.
Reporting: View detailed reports and analytics on exam results.