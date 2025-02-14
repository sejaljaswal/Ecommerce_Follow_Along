# Follow-Along E-Commerce Website

## Key Features

### 1. REST API
- Implements RESTful principles for efficient client-server communication.
- Endpoints for managing products, users, and orders.

### 2. MERN Stack
- Built with MongoDB, Express.js, React, and Node.js.
- Ensures scalability, performance, and a seamless full-stack experience.

### 3. Order Handling
- Streamlined order processing from cart to checkout.
- Real-time updates for order status and inventory management.

### 4. Product Listing & Management
- Features for adding, editing, and removing products.
- Search and filter functionality for an optimized user experience.

### 5. User Authentication
- Secure authentication with JWT.
- Role-based access control for users and admins.

---

## Project Milestones

### **Milestone 2: Project Setup** 🚀

✅ **Project Initialization**
- Structured the project with separate frontend and backend directories.
- Initialized a React app for the frontend and a Node.js server for the backend.

✅ **Tooling & Configuration**
- Configured Tailwind CSS for modern and responsive styling.
- Added useful extensions to improve development efficiency.

✅ **Login Page Implementation**
- Designed and developed a fully functional Login Page.
- Ensured proper UI styling using Tailwind CSS.
- Set up basic authentication logic to handle user login.

📌 *This milestone laid the groundwork for the E-Commerce application by setting up the project structure and implementing the first user-facing feature.*

---

### **Milestone 3: Backend Infrastructure Setup** 🚀

✅ **Backend Folder Structure**
- Organized backend code with separate folders for routes, controllers, models, and middleware.
- Introduced utils and middleware directories for better modularity.

✅ **Server Setup**
- Created a backend server using Node.js and Express.
- Configured the server to listen on a designated port.

✅ **Database Connection**
- Integrated MongoDB to store and manage data.
- Verified successful connection between the server and MongoDB.

✅ **Error Handling**
- Implemented a global error handler for better debugging.
- Provided meaningful error messages for invalid requests and failed operations.

✅ **README Update**
- Documented Milestone 3 progress in the README file.

📌 *This milestone focused on setting up a solid backend infrastructure to support the application’s growth and data management.*

---

### **Milestone 4: Creating User Model and Controller** 🚀

✅ **User Model Implementation**
- Defined a User Schema using Mongoose to store user details (name, email, password, etc.).
- Implemented necessary validations to ensure data integrity.
- Integrated bcrypt for secure password hashing.

✅ **User Controller Setup**
- Developed controller functions to:
  - Create new users.
  - Retrieve user details.
  - Update user information.
  - Delete users if necessary.
- Handled error responses for invalid or duplicate user entries.

✅ **Multer File Upload Integration**
- Configured Multer to handle file uploads (e.g., profile pictures).
- Implemented logic to store and retrieve uploaded images.
- Ensured file validation to prevent invalid file types from being uploaded.

✅ **Project Submission**
- Pushed the updated code to GitHub.
- Updated the README with Milestone 4 details.

📌 *This milestone strengthened the user management aspect of our application, making it more robust and scalable for future enhancements.*

---

### **Milestone 5: Creating the Signup Page** 🚀

✅ **Sign-Up Page UI Development**
- Created the user interface for the Sign-Up page using HTML and Tailwind CSS.
- Included fields for name, email, and password.
- Designed the page to be user-friendly and visually appealing.

✅ **Form Validation**
- Implemented client-side form validation to ensure data quality.
- Validated email format, password strength (e.g., minimum length), and other necessary fields.
- Provided user-friendly error messages for invalid inputs.

✅ **README Update**
- Documented Milestone 5 progress in the README file.

📌 *This milestone focused on creating the user registration interface and ensuring that the data entered by the user is valid before being sent to the backend. This improves user experience and reduces the load on the server.*

---

### **Milestone 6: Backend Signup Endpoint and Password Encryption** 🚀

✅ **Signup Endpoint Implementation**
- Created a new route and controller function to handle POST requests to the signup endpoint.
- Received user data from the frontend signup form.

✅ **Password Encryption**
- Used bcrypt to hash the user's password before storing it in the database.
- Ensured that passwords are never stored in plain text.

✅ **User Data Storage**
- Stored the complete user data (name, email, hashed password, etc.) in the MongoDB database.
- Implemented error handling for duplicate entries and other potential issues.

✅ **README Update**
- Documented Milestone 6 progress in the README file.

📌 *This milestone focused on securely handling user registration on the backend, including the crucial step of password encryption. This is essential for protecting user data and maintaining security best practices.*

---

# Milestone 7 - Login Endpoint

## Overview
This milestone involves creating a login endpoint that allows users to authenticate using their email/username and password.

## Steps

### 1. Create Login Endpoint
- Accept user credentials (email/username and password).
- Retrieve the corresponding user from the database.

### 2. Validate Password
- Use bcrypt to hash the entered password.
- Compare it with the stored hashed password for authentication.

## Technologies Used
- Node.js / Express (or relevant backend framework)
- bcrypt for password hashing
- Database (MongoDB, PostgreSQL, etc.)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the application:
   ```sh
   npm start
   ```

## API Endpoint
### Login
**POST** `/api/login`
#### Request Body
```json
{
  "email": "user@example.com",
  "password": "yourpassword"
}
```
#### Response
```json
{
  "message": "Login successful",
  "token": "your-jwt-token"
}
```

## License
This project is licensed under the MIT License.

---


