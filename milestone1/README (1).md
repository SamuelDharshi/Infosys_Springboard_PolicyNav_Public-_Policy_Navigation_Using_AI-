# Milestone 1 – User Authentication System

## Project Title
User Authentication System – Milestone 1

## Description of what was implemented in Milestone 1

In this milestone, a secure user authentication system was developed using Streamlit, JWT, and Ngrok.

The application allows users to create an account, log in securely, reset their password, and access a protected dashboard page after successful authentication.

This milestone focuses only on user authentication and basic session handling.

## Features Implemented

- User signup with validation
- Secure login using JWT
- Dashboard page displayed after successful login
- Forgot password functionality
- Ngrok integration to expose the local application

## Steps to run the application

1. Install the required dependencies:

2. Run the Streamlit application:

streamlit run app.py


Start ngrok to expose the application:

ngrok http 8501

Open the public ngrok URL in your browser.

```bash
pip install streamlit pyjwt pyngrok
```

Screenshots
Signup Page
<img width="1131" height="829" alt="Screenshot 2026-02-14 083619" src="https://github.com/user-attachments/assets/7b055d52-71df-482f-be31-383b81a0c549" />

Login Page
<img width="1129" height="635" alt="Screenshot 2026-02-14 083605" src="https://github.com/user-attachments/assets/1a1d1ae5-3c47-45f7-9f56-1bab3fb169a2" />

Dashboard

The dashboard is the page shown after a successful login.

<img width="1309" height="499" alt="image" src="https://github.com/user-attachments/assets/3c94f84e-de0d-431a-93ac-4494b63196e0" />

Forgot Password Page

<img width="1045" height="408" alt="image" src="https://github.com/user-attachments/assets/22a2ddc7-caac-4b71-9bad-d6acbb0391a7" />

###working url : https://irrevocable-darell-martyrly.ngrok-free.dev/
