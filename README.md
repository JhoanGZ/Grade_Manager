# Student Management System

## Description
This project is a Java-based Student Management System developed for Colegio Latinoamericano to manage grades for 1st-year high school students. The application allows for student data management, subject assignment, grade entry, and average calculation.

## Features
- Menu-driven console application
- Student creation and management
- Subject assignment to students
- Grade entry for subjects
- Average grade calculation
- Data export to text file

## Project Structure
The project is organized into the following packages:
- `vistas`: Contains classes for the user interface
- `modelos`: Contains data model classes
- `servicios`: Contains service classes for business logic
- `utilidades`: Contains utility classes

## Key Classes
- `MenuTemplate`: Abstract class defining the structure of the menu
- `Menu`: Concrete implementation of the menu
- `Alumno`: Represents a student
- `MateriaEnum`: Enumeration of available subjects
- `Materia`: Represents a subject with its grades
- `AlumnoServicio`: Manages student-related operations
- `ArchivosServicio`: Handles file operations
- `PromedioServicioImp`: Calculates grade averages

## Getting Started
1. Clone the repository
2. Open the project in Eclipse as a Maven project
3. Run the main application class

## Usage
The application presents a menu with the following options:
1. Create Students
2. List Students
3. Add Subjects
4. Add Grades
5. Exit
6. Export Data

Follow the on-screen prompts to navigate through the application.

## Testing
The project includes unit tests for `PromedioServicio` and `AlumnoServicio` using JUnit 5 and Mockito.

## Dependencies
- JUnit 5
- Mockito

## Export Format
The exported data will be in a text file with the following format:
```
Student: [RUT] - [Name]
Subject: [Subject Name] - Average: [Average Grade]
```

## Contributing
This project is part of a school assignment. Contributions may be limited, but feel free to fork the project for your own use or study.

## License
[Include appropriate license information here]
