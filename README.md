# Vendor Portal Registration

**Note: Node modules have been deleted from the GitHub repository. Kindly download them before running the application!**

## Introduction

This is a vendor portal registration application built to enable local designers, vendors, and boutiques to register themselves and showcase their collections on Myntra. The application includes both registration and login functionalities, and it leverages MongoDB for storing user data.

## Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, JavaScript, Handlebars (hbs)
- **Database**: MongoDB
- **Authentication**: bcrypt.js, JSON Web Token (JWT)
- **Templating Engine**: Handlebars (hbs)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-repo-url.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd your-repo-directory
   ```

3. **Install the dependencies:**

   ```bash
   npm install
   ```

## Usage

1. **Start the MongoDB server:**

   Make sure your MongoDB server is running.

2. **Start the application:**

   ```bash
   node app.js
   ```

3. **Open your browser and navigate to:**

   ```text
   http://localhost:3000
   ```

## Features

### Registration Form

- **First Name**
- **Last Name**
- **Email**
- **Phone Number**
- **Gender**
- **Age**
- **Password**
- **Confirm Password**

### Login Form

- **Email**
- **Password**

## Code Overview

### Backend (app.js)

- **Dependencies**: Express, Path, Handlebars, bcrypt.js, JSON Web Token, Mongoose
- **Routes**:
  - GET `/` - Renders the home page
  - GET `/register` - Renders the registration form
  - GET `/login` - Renders the login form
  - POST `/register` - Handles user registration
  - POST `/login` - Handles user login

### Frontend (register.hbs)

- **HTML Structure**:
  - Registration and login forms with Bootstrap styling
  - Navigation tabs for switching between registration and login

## Important Notes

1. **Node Modules**:
   - Node modules are excluded from the GitHub repository. Run `npm install` to download the necessary dependencies.
  
2. **MongoDB Connection**:
   - Ensure that your MongoDB connection string is correctly set in the `conn.js` file.

3. **Environment Variables**:
   - Set up the necessary environment variables for JWT secret and other configurations.

## License

This project is licensed under the MIT License.
