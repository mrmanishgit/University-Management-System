# University-Management-System
Technologies Used
Java: The core programming language used for implementing the system logic.
JavaFX: Used for building the graphical user interface (GUI) of the application.
MySQL: Used as the database management system for storing and retrieving data related to students, courses, faculty, and other entities.
JDBC: Java Database Connectivity is utilized for connecting Java applications with relational databases like MySQL.
Maven: Dependency management tool used for managing project dependencies and building the project.
Setup
Clone the Repository:
![Screenshot 2024-05-31 204300](https://github.com/mrmanishgit/University-Management-System/assets/157808382/bb09565e-c715-424d-b7a9-116d768fc5c3)

bash
Copy code
git clone https://github.com/yourusername/university-management-system.git
Database Setup:
![Screenshot 2024-05-31 204342](https://github.com/mrmanishgit/University-Management-System/assets/157808382/ba09ae02-8c9c-41b4-a431-d38adbc42a2d)

Install MySQL if not already installed.
Create a new database named university_management.
Execute the SQL script university_management.sql located in the database folder to create the necessary tables and populate initial data.
Configure Database Connection:

Update the database connection properties in the config.properties file located in the src/main/resources folder with your MySQL database credentials.
Build and Run:
![Screenshot 2024-05-31 204400](https://github.com/mrmanishgit/University-Management-System/assets/157808382/820ef5b8-9926-4393-80e1-79958b719283)

Open the project in your preferred Java IDE.
Build the project using Maven.
Run the Main class to start the application.
![Screenshot 2024-05-31 204418](https://github.com/mrmanishgit/University-Management-System/assets/157808382/6672e2d6-6c94-48a1-a2e0-71dce86bbd44)
![Screenshot 2024-05-31 204450](https://github.com/mrmanishgit/University-Management-System/assets/157808382/bcb6672c-5a9f-4217-9fa4-6e6cdd7e5d34)
![Screenshot 2024-05-31 204521](https://github.com/mrmanishgit/University-Management-System/assets/157808382/090706ea-36dd-4542-8387-ea3e8c60da96)

Usage
Upon launching the application, users will be presented with a login screen where they can enter their credentials.
Depending on the user role (administrator, faculty, or student), different functionalities will be available.
![Screenshot 2024-05-31 204536](https://github.com/mrmanishgit/University-Management-System/assets/157808382/3528fdcb-2fac-4af4-8849-cb44690b56d7)

Users can navigate through the various![Screenshot 2024-05-31 204435](https://github.com/mrmanishgit/University-Management-System/assets/157808382/8c42fd4c-5a84-47b8-af03-65eb352dd72d)
 modules of the system (e.g., student management, course management) using the menu options provided in the GUI.
 ![Screensho![Screenshot 2024-05-31 204604](https://github.com/mrmanishgit/University-Management-System/assets/157808382/83c861cc-865b-4b00-a47a-f6aec7fdd50c)
t 2024-05-31 204552](https://github.com/mrmanishgit/University-Management-System/assets/157808382/e8fedac9-f74d-4b66-9185-1fbfc9edbda2)

![Screenshot 2024-05-31 204634](https://github.com/mrmanishgit/University-Management-System/assets/157808382/eaf66d0d-8d52-48f3-b1ff-e61fd9b32890)

Perform necessary actions such as adding new records, updating existing ones, enrolling in courses, etc.
Log out of the application after completing the tasks.
