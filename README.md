CODETECH-TASK1

hospital_management_system

Company : CODTECH IT SOLUTIONS

ID: CT08DS4710

Domain: JAVA PROGRAMMING

Duration: july 10 to july 25

Overview of Hospital Management System

Purpose The Hospital Management System is designed to manage various aspects of a hospital's operations efficiently. It allows for the handling of patient information, ambulance services, department details, employee records, and room assignments.

Key Features

Patient Information Management:

Add, update, delete, and search patient records. Store patient details like name, age, gender, contact information, medical history, and treatment details.

Ambulance Management: Track ambulance availability and assignments. Record details such as ambulance number, driver information, and status (available, on duty, maintenance).

Department Management: Manage hospital departments (e.g., Cardiology, Neurology, Orthopedics). Store department details including department name, head of department, and contact information.

Employee Information Management: Maintain records of hospital staff including doctors, nurses, administrative staff, and other employees. Store employee details such as name, designation, contact information, salary, and department assignment.

Room Management: Manage room availability and assignments. Record details such as room number, type (e.g., general, ICU, private), and current occupancy status.

Technologies Used Java: Core programming language for the application. Java Swing: GUI toolkit for creating the graphical user interface. JDBC (Java Database Connectivity): API for connecting and executing queries on the database.

System Architecture

GUI Layer (Java Swing): Provides a user-friendly interface for hospital staff to interact with the system. Contains forms and tables for displaying and managing data. Handles user input and triggers appropriate actions.

Service Layer: Contains business logic for various operations (e.g., adding a patient, assigning an ambulance). Validates data and ensures proper flow of operations.

DAO Layer (Data Access Object): Manages database operations using JDBC. Contains methods for CRUD (Create, Read, Update, Delete) operations on the database.

Database: Stores all the data related to patients, ambulances, departments, employees, and rooms. Can be any relational database (e.g., MySQL, PostgreSQL).
