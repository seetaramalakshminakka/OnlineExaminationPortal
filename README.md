# Online Examination Portal

## Overview
The **Online Examination Portal** is a web-based application that allows students to register, take exams, view their scores, and manage their profiles efficiently. The system ensures smooth examination processes with a user-friendly interface and secure login functionalities.

## Features
- **User Registration & Login**: New users can sign up, and existing users can log in using their credentials. A password recovery feature is also available through nickname validation.
- **Main Menu**: Upon login, users can:
  1. View Profile
  2. View Score
  3. Take Exam
  4. Logout
- **Profile Management**: Users can view their biodata, exam scores, and rank.
- **Exam Module**: Randomized questions are generated for each test. Users can take the exam once. The system prevents re-taking of exams after submission.
- **Secure Exam Environment**: Exam results are calculated and displayed immediately after submission.

## Screenshots

### Home Page
_The first page users see on loading the portal._

![Home Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.36.13.jpeg)

### Login Page
_Users are required to log in with their credentials._

![Login Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.37.45.jpeg)

### Registration Page
_New users can register by providing necessary details._

![Registration Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.42.11.jpeg)

## User Workflow

1. **Home Page**: Users can either log in or register if they are new.
2. **Login**: Registered users can log in. If they forget their password, they can recover it by providing the nickname they set during registration.
3. **Main Page**: After logging in, users are directed to the main page with four options:
   - **View Profile**: Displays biodata, scores, and rank. Navigation button redirects back to the main page.
   - **View Score**: Shows the user's score and grade if they have already taken an exam. If not, prompts the user to take the exam.
   - **Take Exam**: Generates a random set of questions for the user. If the user has already taken the exam, they receive a message stating "Exam already taken."
   - **Logout**: Ends the session and returns the user to the login page.
4. **Exam Module**: After taking the exam, the score is displayed immediately, and the user is redirected back to the main page.
5. **Session Management**: After logout, the user's session is terminated.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Framework**: Angular
- **Tools**: VS Code, Postman (for API testing)

## Installation & Setup

### Prerequisites
- **Node.js** (version 14.x or above)
- **MongoDB** (local or cloud-based)
- **Angular CLI** (version 12.x or above)

### Clone the Repository
```bash
git clone https://github.com/yourusername/online-examination-portal.git
cd online-examination-portal

