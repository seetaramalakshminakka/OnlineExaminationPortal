# Online Examination Portal

## Overview
The **Online Examination Portal** is a web-based application that allows students to register, log in, take exams, and view their scores. The portal offers a streamlined process for managing online exams while ensuring a smooth user experience.

## Features Overview

### 1. Home Page
The **Home Page** is the first page users see when they access the portal. It contains options to either log in or register as a new user.

![Home Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.36.13.jpg)

**Redirection**:  
- Clicking on **Login** redirects to the **Login Page**.
- Clicking on **Register** redirects to the **Registration Page**.

---

### 2. Login and Registration
- **Login**: Existing users can enter their username and password to access the portal.
- **Registration**: New users can sign up by providing their details and creating login credentials.

**Login Page:**
![Login Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.37.45.jpeg)

**Redirection**:  
- Successful login redirects to the **Main Page**.
- Clicking **Forgot Password** redirects to the **Forgot Password Page**.

**Registration Page:**
![Registration Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.42.11.jpeg)

**Redirection**:  
- Successful registration redirects to the **Login Page**.

---

### 3. Forgot Password
If users forget their password, they can recover it by providing the nickname they entered during registration. Once matched, they can reset their password.

![validation page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.40.46.jpeg)

If matched then it opens **RESET PASSWORD** page.

![Forgot Password Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.41.07.jpeg)

On reseting password the password is **sucessfully updated**in database.

![successful updation](public/images/WhatsApp%20Image%202024-10-27%20at%2018.41.46.jpeg)

**Redirection**:  

- After resetting the password, the user is redirected back to the **Login Page**.
---
### 4. Main Page (After Login)
Once logged in, users are taken to the **Main Page**, where they can choose from four options:
1. **View Profile**
2. **View Score**
3. **Take Exam**
4. **Logout**

![Main Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.38.14.jpeg)

**Redirection**:  
- Clicking **View Profile** redirects to the **Profile Page**.
- Clicking **View Score** redirects to the **View Score Page**.
- Clicking **Take Exam** redirects to the **Exam Page**.
- Clicking **Logout** redirects back to the **Login Page** and ends the session.

---

### 5. View Profile
The **View Profile** section allows users to see their biodata, scores, and rank. There’s also a button to return to the main menu.

![Profile Page](public/images/WhatsApp%20Image%202024-10-27%20at%2018.39.40.jpeg)

**Redirection**:  
- Clicking the **Back to Main Page** button redirects back to the **Main Page**.

---

### 6. View Score
The **View Score** page displays the user’s score and grade, provided the exam has been taken. If not, it prompts the user to take the exam.

- **If the exam has already been taken**:
  ![View Score](public/images/WhatsApp%20Image%202024-10-27%20at%2018.38.58.jpeg)

**Redirection**:  
- If no exam is taken, clicking **Take Exam** redirects to the **Exam Page**.
- Clicking **Back to Main Page** redirects to the **Main Page**.

---

### 7. Take Exam
The **Take Exam** page generates a random set of questions for the user to answer. If the user has already taken the exam, they will see a message saying "Exam already taken."

- **Exam Page** (Before submission):
  ![Take Exam](public/images/WhatsApp%20Image%202024-10-27%20at%2018.42.34.jpeg)

- **Exam Already Taken**:
  ![Exam Taken](public/images/WhatsApp%20Image%202024-10-27%20at%2018.40.28.jpeg)

**Redirection**:  
- After submitting the exam, the score is shown, and clicking **OK** redirects to the **Main Page**.

---

### 8. Submit Exam and View Results
Once the exam is completed and submitted, the user’s score is immediately displayed, and they are redirected back to the main page after confirmation.

![Submit Exam](public/images/WhatsApp%20Image%202024-10-27%20at%2018.43.00.jpeg)

**Redirection**:  
- Clicking **MAIN MENU** after viewing the score redirects back to the **Main Page**
---

### 9. Logout
The **Logout** option logs the user out and redirects them to the **Login Page**, ending their session.
---

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
