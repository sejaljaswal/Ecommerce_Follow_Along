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

---


### Milestone 8: 
**Product Card Component and Homepage Layout 🚀

✅ Frontend Product Card Component
Designed and implemented a reusable Product Card component.
Utilized props to dynamically render product details like name, image, and price.

✅ Homepage Layout for Products
Created a responsive homepage to display multiple Product Cards.
Used Grid/Flexbox for optimal layout and user experience.


# Milestone 9: Product Input Form 🚀
✅ Product Form Implementation
Designed a form for adding product details such as name, price, and description.
Implemented an option for uploading multiple product images.

✅ Database Integration
Structured the form to send product data to the backend for storage in MongoDB.
Ensured proper validation and error handling.

✅ README Update
Documented Milestone 9 progress in this README file.
This milestone focused on enabling product input, which is essential for expanding the e-commerce platform by allowing users to add new products dynamically.




# Milestone 10: Product Schema and API Endpoint 🚀

✅ Product Schema Implementation
Defined a Product Schema in Mongoose.
Implemented validation for fields like name, price, and image URL.

✅ API Endpoint for Adding Products
Created a POST endpoint to store product details in MongoDB.
Ensured proper validation before saving the data.


# Milestone 11: Dynamic Product Display 🚀

✅ Fetching Product Data
Created an endpoint to retrieve all stored products from MongoDB.
Implemented API call logic in the frontend to fetch data dynamically.

✅ Displaying Products
Passed fetched product data to the Product Card component.
Rendered product information dynamically on the homepage.




# Milestone 12: My Products Page 🚀

✅ Filtering Products by User Email
Created a backend endpoint to retrieve products associated with the logged-in user's email.
Queried the MongoDB database to fetch only those products matching the user's email.

✅ Fetching Data on the Frontend
Implemented an API call to request user-specific product data from the backend.
Stored the retrieved data in the application state for dynamic rendering.

✅ Displaying User's Products
Passed the fetched data to the Product Card component.
Rendered the products dynamically on the "My Products" page.



# Milestone 13: Editing Uploaded Products 🚀
✅ Backend Update Endpoint
Created an endpoint to receive and update product details in MongoDB.
Implemented logic to find the product by its ID and modify the existing data.
✅ Frontend Edit Button
Added an Edit button to each product card.
When clicked, it fetches the product details and auto-fills the form.
✅ Updating Product Data
Allowed users to modify product details directly within the form.
Implemented a Save Changes feature to update product details in the database.


# Milestone 14 Progress Summary 🚀
In this milestone, I implemented the delete functionality for product data. This involved:

✅ Backend: Added a DELETE API endpoint in Express.js to remove a product from MongoDB using its ID.
✅ Frontend: Integrated a delete button on the product card that triggers an API request to delete the product.
✅ UI Update: Ensured the product list updates dynamically after deletion.
✅ Code Push: Committed and pushed the changes to the GitHub repository.

This milestone helped in understanding how to perform delete operations in a MERN stack application.


# Milestone 15 Progress Summary 🚀

In this milestone, we created and integrated a responsive Navbar to enhance navigation across the application.

✅ Tasks Completed:
Built a Nav component with links to Home, My Products, Add Product, and Cart.
Ensured full responsiveness for smooth navigation on all screen sizes.
Added the Navbar to all pages for a consistent user experience.


#  **Milestone 16 Progress Summary 🚀**  

In this milestone, we **created a Product Info page** to display detailed product data and allow users to select quantity and add items to the cart.  

#### ✅ **Tasks Completed:**  
- Developed a **dedicated Product Info page** for individual product details.  
- Implemented a **quantity selector** to allow users to choose the desired amount.  
- Added an **"Add to Cart"** button for seamless shopping experience.  

#### 🔍 **Next Steps:**  
- Improve UI for better product presentation.  
- Ensure smooth cart functionality.  
- Test responsiveness on different devices.  

This milestone enhanced our understanding of **dynamic product pages and user interactions** in e-commerce applications. 🚀
Improve UI design for better accessibility.
Test responsiveness across different devices.
Optimize navigation for seamless performance.
This milestone helped in understanding Navbar creation and multi-page navigation in web applications. 🚀


# 📌 Milestone 17: Implementing Cart Functionality

#### ✅ Achievements
Updated User Schema: Added a cart field to store selected products.
Created Cart Schema: Structured database model for cart items.
Developed API Endpoints:
POST /cart/add → Add products to the cart.
GET /cart → Retrieve cart items.
DELETE /cart/remove/:productId → Remove product from cart.
MongoDB Integration: Persistent cart storage.
Validation & Error Handling: Prevented duplicate entries, ensured correct data format.



# 📌 Milestone 18: Fetching Cart Items

#### ✅ Achievements
Created Backend Endpoint:
GET /cart/:email → Fetches all products in a user’s cart using their email.
Implemented Business Logic: Retrieved cart data from the database for the logged-in user.
Integrated MongoDB: Ensured persistent storage and retrieval of cart items.
Optimized API Response: Sent structured cart data for frontend display.

# Milestone 19 - Cart Functionality

🚀 What was achieved in this milestone?
In Milestone 19, we implemented the cart functionality in our eCommerce project. The following tasks were completed:

🛒 Cart Page UI
Created a frontend cart page to display products inside the cart.
Fetched cart data using the API endpoint built in Milestone 18.
For each product, added + and - buttons to increase and decrease quantity.

🔄 Backend API for Quantity Update
Implemented a backend API endpoint to handle quantity updates.
The endpoint allows users to increase or decrease the quantity of products in the cart.
Ensured proper validation to prevent negative quantities.

📌 Steps Followed
Created the Cart page UI in the frontend.
Integrated the UI with the backend API.
Built an endpoint to modify product quantities in the cart.
Tested functionality to ensure smooth updates.



# Milestone 20 - Profile Page and Backend Endpoint

🚀 What was achieved in this milestone?
In Milestone 20, we successfully implemented a user profile page on the frontend and created a backend endpoint to fetch user data. The following tasks were completed:

👤 Profile Page UI
Designed and developed a profile page to display user information.
Displayed the profile photo, name, and email in one section.
Added a separate section to display addresses with an "Add Address" button.
Implemented logic to show "No address found" if no addresses are available.

🔄 Backend API for User Data
Created an API endpoint to retrieve user data, including profile photo, name, email, and addresses.
Implemented functionality to send user data via mail.

📌 Steps Followed
Created the profile page UI in the frontend.
Integrated the UI with the backend API.
Built an endpoint to fetch and send user data.
Tested functionality to ensure proper data retrieval and display.


# Milestone 21 - Address Form Page

🚀 What was achieved in this milestone?
In Milestone 21, we successfully implemented an address form page to collect user address details. The following tasks were completed:

📋 Address Form UI
Designed and developed an address input form.
The form collects the following details:
Country
City
Address Line 1
Address Line 2
Zip Code
Address Type (Home/Work/Others)

🔄 Navigation & State Management
Created a state to store the address input.
Implemented navigation from the profile page when clicking on "Add Address".

📌 Steps Followed
Created a new address form page in the frontend.
Implemented form validation for required fields.
Linked the form page to the profile page with a navigation button.
Tested functionality to ensure smooth data entry.

# Milestone 22 - Storing User Address in Database

Overview
In this milestone, we have implemented a backend endpoint that allows users to save their address inside their profile in the database. This functionality is crucial for managing user information in an e-commerce platform.

Learning Goals 🎯
Create a backend endpoint to store the address inside the user profile in the database.
Understand how to receive data from the frontend and update the user collection accordingly.

Implementation Steps 📝
Created an API endpoint to receive address details from the frontend form.
Updated the User Model to ensure that addresses are stored in an array within the user collection.
Implemented Database Update Logic to push the new address into the user profile.
Tested the Endpoint using Postman to ensure successful address storage.




 # Milestone 23: Address Selection for Orders 🛒
✅ Cart Page Enhancement

Added a "Place Order" button inside the cart page.
Navigated to the "Select Address" page when clicked.
✅ Address Selection Page

Displayed all available addresses of the user.
Provided an option to select one address for the order.

✅ Backend API Implementation
Created an endpoint to fetch and send all saved addresses of the user.
Ensured authentication and proper error handling.




# Milestone 24 - Implementing Place Order Functionality  

## Overview  
In this milestone, we have successfully implemented the **Place Order** functionality. This includes:  
- Displaying all the products in the order.  
- Showing the selected delivery address.  
- Calculating and displaying the total cart value.  
- Adding a "Place Order" button to finalize the purchase.  

## Learning Outcomes  
- Understanding how to manage and display order details.  
- Handling user-selected delivery addresses.  
- Implementing order confirmation logic.  

## Repository Details  
This repository contains the code for Milestone 24. You can find all the relevant changes in the latest commit.  

## Submission  
- Code has been pushed to the GitHub repository.  
- The repository is publicly accessible.  
- This README file summarizes the milestone.

- # Milestone 25: Place Order Endpoint
Overview
In this milestone, we created a backend endpoint to handle the order placement process. This endpoint receives product details, user information, and address details to store the order in MongoDB.

Learning Goals
Create a backend endpoint for placing an order.
Retrieve the user _id using their email.
Store order details in the MongoDB orders collection.

Implementation Steps
Receive Order Data

The endpoint accepts the user's email, product details, and address.
Retrieve User ID
Use the email to find the corresponding _id from the users collection.
Create Orders
For each product, generate a separate order while keeping the same address.

Store Orders in MongoDB
Save the order details using the existing Order Schema.


## Milestone 27: My Orders Page

### 🎯 What was achieved in this milestone:

- Created a **My Orders** page in the frontend to display all user-specific orders.
- Integrated with the backend using a **GET request** to the `/my-orders` endpoint.
- Passed the **user's email** as a query parameter to fetch their orders.
- Displayed order details including product name, price, and order date.
- Enhanced user experience by adding **My Orders** to the **navigation bar** for easy access.
- Successfully connected frontend and backend for order retrieval.

### 📂 Files Modified:
- `src/pages/MyOrders.jsx` — New page to display user orders.
- `src/components/Navbar.jsx` — Added My Orders link to navigation.
- `README.md` — Updated with milestone summary.

### 🔗 Live Preview / Demo:
_If deployed, include a link here (optional)._

### 📌 How to Test:
1. Login with a registered user account.
2. Navigate to `My Orders` via the navbar.
3. View your orders retrieved from the backend.



## 📝 Milestone 28 – Cancel Order Feature
✅ Goal:
Enable users to cancel their orders from the My Orders page.

🔧 Steps:
Frontend:

Show a "Cancel Order" button next to each order.

Only display the button if the order is not already canceled.

On click, send the orderId to the backend using a POST request.

Backend:

Create an endpoint to receive the orderId.

Fetch the order using the ID.

If the order exists and isn't already canceled, update its status to "canceled" and save.


## 📝 Milestone 29 – Setup PayPal Integration (Step 1)
✅ Goal:
Prepare your project for integrating PayPal as an online payment method alongside Cash on Delivery (COD).

🔧 Steps:
Create PayPal Developer Account:

Go to the PayPal Developer Dashboard.

Log in and navigate to Sandbox Accounts.

Sandbox Setup:

Copy the User ID of your sandbox buyer account.

Find your Client ID under Apps & Credentials and save it.

Order Confirmation Page:

Add two radio buttons for payment options:

Cash on Delivery (COD)

Online Payment (PayPal)

When Online Payment is selected, display placeholder PayPal buttons (real functionality comes in the next milestone).


## 💳 Milestone 30 - Online Payment Integration using PayPal API
📚 What was achieved in this milestone:
In this milestone, we learned how to integrate online payment functionality using the PayPal API in a React application. This continued from Milestone 29, where we created a PayPal Sandbox account and retrieved the Client/User ID.

✅ Key Accomplishments:
Installed the @paypal/react-paypal-js npm package to simplify PayPal integration.

Used the PayPalScriptProvider component to wrap our payment section and initialize PayPal with our sandbox client-id.

Added a PayPal button to the frontend to allow users to complete payments via PayPal or card.

Implemented a basic payment flow using sandbox mode, simulating how real-world online payments would function.

🔧 Tools & Libraries:
@paypal/react-paypal-js

PayPal Developer Sandbox Environment




## 🧩 Milestone 31 - Global State Management using Redux
📚 What was achieved in this milestone:
In this milestone, we learned how to implement Redux for global state management in a React application. The key focus was to store and manage the user's email globally across all components.

✅ Key Accomplishments:
Installed the react-redux npm package to enable Redux integration in the React app.

Created a store folder with:

store.js: Configured the Redux store and set up the userReducer to manage user email state.

userActions.js: Defined the setEmail action creator to dispatch email updates to the global store.

Used the Provider component from react-redux in index.js to wrap the main App component and connect the store.

Setup global state to store the user’s email, which can later be accessed or updated from any component.













