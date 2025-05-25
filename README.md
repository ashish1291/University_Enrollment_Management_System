
# University Management System - Java Project

A simple Java Swing-based desktop application to manage various operations of a university system, such as login, student and faculty records, leaves, fee details, and utility access (calculator, notepad).

## Features

- **Splash Screen** with animation
- **Login System** with validation
- **Main Dashboard** with menus for:
  - New student/faculty registration
  - View student/faculty details
  - Apply and view leaves
  - Examination marks entry and result view
  - Fee structure and student fee form
  - Utilities: Calculator and Notepad
  - Exit system
- **Add Faculty Form** with validation and auto-generated ID
- **Student Leave Application** form
- JDBC MySQL connectivity

## Technologies Used

- Java (JDK 8+)
- Swing (GUI)
- JDBC (Database connectivity)
- MySQL (Database)
- JCalendar (`com.toedter.calendar.JDateChooser`)



## How to Run

1. Make sure MySQL server is running.
2. Compile the Java files using:

```bash
javac -cp .;mysql-connector-java.jar university/management/system/*.java
```

3. Run the main program:

```bash
java -cp .;mysql-connector-java.jar university.management.system.Splash
```

## Dependencies

- MySQL JDBC Driver
- JCalendar library
