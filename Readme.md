# Employee Management System

An advanced employee management system built using HTML, CSS, Node.js, and MongoDB.This project includes functionalities like user registration, login, and various features to manage employee-related information such as managing employee details, salary, attendance, and leaves.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
The Employee Management System is designed to streamline and simplify the management of employee information. It offers a user-friendly interface for managing attendance, salary, leaves, and employee details, allowing administrators to easily access, update and manage the information.

## Features
- **User Authentication**: Secure registration and login system using MongoDB for data storage.
- **Employee Details Management**: View and edit details of employees.
- **Salary Management**: Manage employee salaries with an intuitive interface.
- **Attendance Tracking**: Track and update employee attendance records.
- **Leaves Management**: Update leave records and track leave requests.

## Technologies Used
- **Frontend**: HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (MongoDB Atlas for cloud storage)

## Setup Instructions

To get a local copy of the project up and running, follow these steps:

### Prerequisites

1. Make sure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed on your machine.
2. Install MongoDB locally or use MongoDB Atlas (cloud database service).

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/natashagargn/Employee-Management-System-Advanced.git
   
2. Navigate to the project directory:

    ```bash
    cd Employee-Management-System-Advanced

3. Install the required dependencies:
    ```bash
    npm install

4. Update the MongoDB connection string in App.js:
    ```bash
    const dbconnect = 'your_mongodb_connection_string';

5. Start the application:
    ```bash
    node App.js

6. To view the application, open index.html by pasting the file path directly into our browser. It should look something like this:
file:///your_path_to_project/Employee-Management-System-Advanced/index.html

## Usage

1. Register a new user account and log in.
2. Use the navigation to access different sections:
- **Employee Details**: View and edit individual employee records.
- **Salary Management**: Manage and update employee salary information.
- **Attendance**: Record and view employee attendance.
- **Leaves Management**: Update and track leave records.
