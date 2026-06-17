# Student-Management-System


A web-based Student Management System developed using Node.js, Express.js, MySQL, HTML, CSS, and JavaScript. The application provides an efficient way to manage student records through a user-friendly interface and secure backend services.

## Features

* Add new student records
* View all students
* Update student information
* Delete student records
* Search students by name
* Department-wise organization
* Secure authentication and authorization
* Input validation and error handling
* Responsive user interface

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MySQL

### Additional Packages

* bcrypt
* jsonwebtoken
* mysql2
* express-validator
* cors
* dotenv

## Project Architecture

The application follows a modular architecture consisting of:

* Routes
* Controllers
* Models
* Middleware
* Database Layer

This structure improves maintainability, scalability, and code organization.

## Installation

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file:

```env
PORT=3000

DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=student_management

JWT_SECRET=your_secret_key
```

### Start the Application

```bash
npm start
```

or

```bash
npm run dev
```

## Database

The system uses MySQL for storing student and user information.

### Main Tables

#### Students

* Student ID
* Name
* Email
* Phone Number
* Department

#### Users

* User ID
* Username
* Email
* Password

## API Functionalities

### Authentication

* User Registration
* User Login
* JWT Authentication

### Student Management

* Create Student
* Read Student Records
* Update Student Details
* Delete Student Records
* Search Students

## Future Enhancements

* Attendance Management
* Result Management
* Export Reports
* Email Notifications
* Analytics Dashboard

## Author

Gauri Dalvi

## License

This project is intended for educational and learning purposes.
