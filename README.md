# TLC — Three-Level Connect

TLC now stands for Three-Level Connect — representing the three core stages of user interaction: Registration → Authentication → Access.

## About the Project

TLC (Three-Level Connect) is a Django-based web application built to practice and demonstrate a complete user authentication system.

The project focuses on implementing:

User registration
User login
User-specific dashboard access
Admin-side data persistence and management

This project is designed as a learning and demonstration tool, showing how authentication systems work in real-world web applications.

## Purpose

The main goal of this project is to:

Practice backend development with Django
Understand authentication flows
Work with user data storage
Build a clean and responsive frontend UI

## Tech Stack

Technology	Purpose

Python (Django)	Backend logic & authentication

HTML	Structure of pages

CSS	Styling and UI design

JavaScript	Interactivity

SQLite	Database (user storage)

VS Code	Development environment

## Screenshots

### Landing Page (Before Login)

<img width="1883" height="875" alt="image" src="https://github.com/user-attachments/assets/0f8e2ef7-b55c-4045-b168-156ba611a34a" />

<img width="1908" height="852" alt="image" src="https://github.com/user-attachments/assets/209e1066-2f9f-4a10-a384-a38541779eee" />

- Entry point of the application

- Options to Sign Up, Sign In or GitHub reporitory

- Custom animation included

---

### Registration Page

<img width="1907" height="866" alt="image" src="https://github.com/user-attachments/assets/31cb2278-0bf3-461d-a3b2-eebebdb5d158" />

- Users create an account

- Data is saved into the database

---

### Login Page

<img width="1908" height="868" alt="image" src="https://github.com/user-attachments/assets/cec7d691-de0e-4b70-9eac-63669d32c647" />


- Existing users authenticate

- Credentials are verified

---

### Main Page (After Login)

<img width="1500" height="733" alt="image" src="https://github.com/user-attachments/assets/6d32a402-af10-427d-ae2a-3d46b0a5ef76" />

- Displays username dynamically

- Accessible only after login

---

### Admin Panel (Database View)

<img width="1908" height="863" alt="image" src="https://github.com/user-attachments/assets/37a8860e-d099-4bc8-a294-eb3f605374d6" />

- Shows stored users

- Confirms real data persistence

Managed via Django Admin

## Project Structure

<img width="600" height="1019" alt="image" src="https://github.com/user-attachments/assets/11c2dae3-9e3f-4c78-8541-eadfdda538d9" />

##  Application Flow

1. User opens landing page

2. Chooses:

  Sign Up → creates account
  
  Sign In → logs into existing account
  
3. After login → redirected to main page
4. Username is displayed
5. Admin can view stored users in Django Admin

## License

This project is for educational purposes only.
