# Student Management System

## Introduction
The Student Management System is a console-based Java application designed to manage student records. It allows you to add, view, update, and delete student information. This project is ideal for learning basic CRUD operations in Java and can be expanded for more complex functionalities.

## Features
- Add a new student.
- View all students.
- Update existing student information.
- Delete a student.
- Exit the application.

## Project Structure
- **Student.java**: Model class representing a student.
- **StudentManagementSystem.java**: Main class containing the logic for managing students.
- **StudentManagementSystemApp.java**: Entry point of the application.

## Requirements
- Java Development Kit (JDK) 8 or higher.

## Installation and Running the Project
1. **Clone the repository** (if using a version control system):
   ```sh
   git clone https://github.com/An1rud/Student-Management-System.git
   ```
   
2. **Navigate to the project directory**:
   ```sh
   cd StudentManagementSystem
   ```
   
3. **Compile the Java classes**:
   ```sh
   javac Student.java StudentManagementSystem.java StudentManagementSystemApp.java
   ```
   
4. **Run the application**:
   ```sh
   java StudentManagementSystemApp
   ```

## Usage
When you run the application, you will see a menu with the following options:
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Exit

### Adding a Student
- Select option `1`.
- Enter the student ID (alphanumeric).
- Enter the student name.
- Enter the student age.

### Viewing All Students
- Select option `2` to view a list of all students in the system.

### Updating a Student
- Select option `3`.
- Enter the student ID of the student you want to update.
- Enter the new name.
- Enter the new age.

### Deleting a Student
- Select option `4`.
- Enter the student ID of the student you want to delete.

### Exiting the Application
- Select option `5` to exit the application.

