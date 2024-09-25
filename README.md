# Interview-Project

---

# UI/Front-end for Interview Experiences Page

This is the front-end web page for a client, a platform designed to provide users with organized interview experiences from various companies. The primary goal of this project is to enhance the user experience by neatly displaying interview insights from different companies.

## Tech Stack

### Frontend:
- **HTML**
- **CSS**
- **Bootstrap**
- **JavaScript**

### Backend:
- **PHP**: Handles user registration and communication with the database.
- **MySQL**: Stores user data, including username, password, and email ID.

## Features
- **Responsive Design**: The website is built using Bootstrap for a modern, mobile-friendly design.
- **Organized Content**: All interview experiences are displayed in a structured and easy-to-navigate manner.
- **User Registration**: Users can sign up with a unique username and password securely stored in a MySQL database.
- **Bot Prevention**: A Google reCAPTCHA is integrated to prevent bot-based registrations.

## Project Overview

This platform was developed during an SDE internship, a platform designed to help users access detailed interview experiences from top product-based and service-based companies. Users can filter through various companies, view interview insights, and contribute their experiences. The front end provides a responsive design using HTML, CSS, Bootstrap, and JavaScript, while the back end uses PHP and MySQL for user management and data storage.



### Backend Flow
1. **User Registration**: Users can register by providing their username, password, and email.
2. **Data Management**: PHP is used to send HTML form data to the MySQL database, where it is securely stored in the user table.

## Issues That were solved

### Problem: Fake Accounts by Bots
The website faced an issue with bots creating fake accounts, filling the database, and using it for advertisements.


## Installation and Setup

To run this project locally:

1. Clone the repository.
2. Set up a **MySQL** database and create a `user` table with columns for `username`, `password`, and `email`.
3. Edit the PHP files to match your database credentials.
4. Upload the project files to your server.
5. Ensure **Google reCAPTCHA** is properly configured by obtaining site keys from [Google reCAPTCHA](https://www.google.com/recaptcha).
