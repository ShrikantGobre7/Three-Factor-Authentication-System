# Three-Factor-Authentication-System

Project Overview:
Create a web-based three-factor authentication system using Python (Flask for the backend), HTML for the front-end, and CSS for styling. The three factors involved in the authentication process are something the user knows (password), something the user has (a mobile device), and something the user is (biometric data).

Project Components:

User Registration and Profile:
Users can register by providing basic information such as username, email, and password.
Additional information is required, such as mobile number and biometric data (e.g., fingerprint or facial recognition).

User Login:
Users enter their username and password.
If the username and password are correct, the system sends an OTP (One-Time Password) to the registered mobile device.
Mobile Device Verification:

The user receives the OTP on their mobile device through mail.
They enter the OTP on the web page to confirm their mobile device's possession.

Biometric Verification:
Users need to provide biometric data (e.g., fingerprint or facial scan) to complete the third factor.
The system verifies the biometric data against the stored data during registration.

Front-End (HTML and CSS):
Create a user-friendly interface for registration, login, and the authentication process.
Implement responsive design for various devices.

Back-End (Flask):
Develop the Flask application for handling user registration, login, and authentication.
Use Flask sessions for user state management.

Project Workflow:
1.User registers by providing personal information, mobile number, and biometric data.
2.User logs in with their username and password.
3.The system sends an OTP to the registered Email ID.
4.User enters the OTP to confirm mobile device possession.
5.User provides biometric data facial scan.
6.The system verifies the biometric data.
7.Upon successful verification of all three factors, the user gains access.
