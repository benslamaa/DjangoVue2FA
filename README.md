# DjangoVue2FA - Two-Factor Authentication with Django and Vue.js

DjangoVue2FA is a project that demonstrates the implementation of two-factor authentication (2FA) using Django as the backend framework and Vue.js for the frontend. It also includes features such as Google authentication, JWT token usage, reset password, and forgot password functionality.

## Features

- Two-Factor Authentication (2FA): Enhances security by requiring users to provide a second form of identification during login.
- Google Authentication: Allows users to log in using their Google accounts for added convenience.
- JWT Token Usage: Implements JSON Web Tokens (JWT) for secure user authentication and authorization.
- Reset Password: Provides users with the ability to reset their passwords in case they forget or need to change them.
- Forgot Password: Offers a password recovery process for users who have forgotten their passwords.

## Getting Started

Follow these steps to set up and run the project locally:

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/DjangoVue2FA.git
   cd DjangoVue2FA

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install backend dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the backend server
python manage.py runserver

# Navigate to the frontend directory
cd frontend

# Install frontend dependencies
npm install

# Start the frontend development server
npm run serve
Access the application at http://localhost:8080 in your web browser.

# Contributing
Contributions are welcome! If you find any issues or have improvements to suggest, feel free to open an issue or create a pull request
