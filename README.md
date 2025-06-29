# attendance-system

## Project Overview
This project implements a complete school attendance management system with secure JWT authentication. It features a login page with credential validation and a protected home page that displays attendance records. The system demonstrates proper client-server interaction between a Spring Boot backend and frontend.

## Technology Stack
- **Backend Framework**: Spring Boot (Java)
- **Frontend**: HTML5, Vanilla JavaScript
- **Authentication**: JSON Web Tokens (JWT)
- **Build Tool**: Maven
- **Styling**: Pure CSS (No frameworks)

## Screenshots
[Login Screen](client/docs/login.png)
[Home Screen](client/docs/home.png)

## Setup Instructions
```bash
# 1. Clone the repository
git clone https://github.com/rajthanusan/attendance-system.git
cd attendance-system

# 2. Start the backend server
cd server
mvn spring-boot:run

# 3. Access the frontend
Open client/login.html in your preferred browser
Enter the following username and password on the login page:
username:admin
password:password123


