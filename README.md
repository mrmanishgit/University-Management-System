# University-Management-System
Technologies Used
Java: The core programming language used for implementing the system logic.
JavaFX: Used for building the graphical user interface (GUI) of the application.
MySQL: Used as the database management system for storing and retrieving data related to students, courses, faculty, and other entities.
JDBC: Java Database Connectivity is utilized for connecting Java applications with relational databases like MySQL.
Maven: Dependency management tool used for managing project dependencies and building the project.
Setup
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/university-management-system.git
Database Setup:

Install MySQL if not already installed.
Create a new database named university_management.
Execute the SQL script university_management.sql located in the database folder to create the necessary tables and populate initial data.
Configure Database Connection:

Update the database connection properties in the config.properties file located in the src/main/resources folder with your MySQL database credentials.
Build and Run:

Open the project in your preferred Java IDE.
Build the project using Maven.
Run the Main class to start the application.
Usage
Upon launching the application, users will be presented with a login screen where they can enter their credentials.
Depending on the user role (administrator, faculty, or student), different functionalities will be available.
Users can navigate through the various modules of the system (e.g., student management, course management) using the menu options provided in the GUI.
Perform necessary actions such as adding new records, updating existing ones, enrolling in courses, etc.
Log out of the application after completing the tasks.
