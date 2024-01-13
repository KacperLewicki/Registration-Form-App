# User Registration and Login System Project Documentation

## Introduction

This document provides detailed information about the user registration and login system, which serves as a foundation for the further development of a web application. The project is built using React for the frontend and Node.js with Express for the backend, with a local SQL database managed by XAMPP.

## System Architecture

### Frontend

- **Technology** : React
- **Features** :
- Registration form for new users.
- Login form for registered users.
- Recruitment form accessible after successful login.

### Backend

- **Technologies** : Node.js, Express
- **Features** :
- Processing requests from registration and login forms.
- Communicating with the SQL database to verify user data.
- Real-time automatic updates using Nodemon.

### Database

- **Management System** : MySQL in XAMPP
- **Data** :
- Storage of user registration and login data.
- Tables with application information post-login.

## Project Setup

### Prerequisites

- Installed Node.js and npm.
- Installed XAMPP with MySQL.
- Installed Git for cloning the project repository.

### Installation and Configuration

- Clone the project repository.
- Open the terminal and navigate to the project directory.
- Run `npm install` in both the main directory and the frontend directory to install all dependencies.
- Configure the database connection in the backend configuration file.
- Run XAMPP and ensure that Apache and MySQL servers are active.
- Import the initial database structure.

## Running the Development Server

- In the backend terminal, run `nodemon` or `npm start` to start the backend server.
- In the frontend terminal, run `npm start` to start the React application.

## Workflow

### User Registration

- The user fills out the registration form and submits the data.
- The backend verifies the data and registers a new user in the database.
- The user receives a registration confirmation.

### Login

- The registered user completes the login form.
- The backend verifies login credentials with the database.
- Upon successful login, the user is directed to the recruitment form.

### Recruitment Form

- The logged-in user has access to the application form.
- Data from the form is sent to the backend and stored in the database.


