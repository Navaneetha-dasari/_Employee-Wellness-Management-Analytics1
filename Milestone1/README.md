# Employee Wellness Management Analytics
## Milestone 1 – User Authentication Module
### Project Objective
The objective of this milestone is to develop a secure user authentication system for the Employee Wellness Management Analytics project using Streamlit. 
This module enables users to register, log in, recover forgotten passwords through email OTP verification, and securely manage their sessions.
User credentials are encrypted using bcrypt, authentication is handled with JWT, and all user information is stored securely in a Neon PostgreSQL database.
## Technologies Used
- Python
- Streamlit
- Neon PostgreSQL
- bcrypt
- JWT (JSON Web Token)
- Google SMTP
- psycopg2
- Email Validator
- Google Colaboratory
## Features Implemented
- Home Page
- User Registration (Sign Up)
- Secure User Login
- Password Encryption using bcrypt
- Email Verification using OTP
- Forgot Password
- Password Reset
- JWT-based Authentication
- Neon PostgreSQL Database Integration
- Secure Session Management
## Google Colab Setup Instructions
1. Open the `Authentication.ipynb` notebook in Google Colab.
2. Install all the required libraries.
3. Configure the Neon PostgreSQL database credentials.
4. Configure the Gmail SMTP email address and App Password.
5. Run all the notebook cells in sequence.
6. Register a new user account.
7. Verify the email using the OTP received.
8. Log in using the verified account.
9. Test the Forgot Password feature and reset the password.
