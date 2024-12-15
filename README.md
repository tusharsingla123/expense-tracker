# expense-tracker

**Project Description**

The Expense Tracker is a full-stack web application that helps users manage their daily expenses efficiently. It offers complete CRUD (Create, Read, Update, Delete) functionality, allowing users to track, categorize, and analyze their spending habits. The frontend is built with React for a seamless user experience, while the backend is powered by Node.js and MongoDB for secure data management. Users can add, view, edit, and delete expense records, with real-time updates and insightful financial forecasts.

**Technical Decisions and Overview**

**Frontend**
* Framework: React.js for a dynamic and interactive user experience.
* Responsive Design: Ensured compatibility across desktop, tablet, and mobile 
  devices using CSS media queries.
* User Interface: Built an intuitive and user-friendly UI for adding, viewing, and 
  editing expense details.
* State Management: Used useState and useEffect hooks for efficient state 
  management and real-time updates.
* Error Handling: Client-side validation to ensure users input correct data (e.g., 
  positive numbers for expenses).

**Backend**
* Framework: Node.js and Express.js to handle API requests and manage the server- 
  side logic.
* Database: MongoDB for secure and scalable data storage of user expenses and 
  records.
* API Endpoints: Exposed RESTful API endpoints for handling CRUD operations.
* Validation: Input validation for expense records, ensuring correct data formats 
  and required fields.
* Error Handling: Implemented proper error responses for client and server errors to maintain a robust system.

**Data Management**
* Database: MongoDB used for its flexibility and scalability to store user records.
* CRUD Operations: Full CRUD capabilities, allowing users to create, view, edit, 
  and delete expense entries.
* Financial Forecasting: Includes predictive insights to help users manage future 
  expenses by factoring in inflation rates.


## Setup Instructions

**Prerequisites**
* Node.js
* MongoDB

**Installation**
* Clone the Repository:
     ```bash
     git clone https://github.com/yourusername/expense-tracker.git
     cd expense-tracker
     ```
* Install Server Dependencies: Navigate to the backend folder and install dependencies
  ```bash
  cd backend
  npm install
  ```
* Install Client Dependencies: Open a new terminal window, navigate to the frontend folder, and install dependencies
  ```bash
  cd frontend
  npm install
  ```
* Configure Environment Variables: Create a .env file in the backend directory and specify the following environment variables
  ```bash
  PORT=8000
  MONGODB_URI=mongodb://localhost:27017/exp
  ```
* Database Setup: Ensure MongoDB is running locally or modify the MONGODB_URI in the .env file to match your database setup.
* Run the Backend Server: Start the backend server in the backend folder
  ```bash
  cd backend
  npm start
  ```
   The server will start at http://localhost:8000.
* Run the Frontend Server: Start the React frontend in the frontend folder.
  ```bash
  cd frontend
  npm start
  ```
   The frontend will be accessible at http://localhost:3000.

## Project Structure

**Backend**
* Routes: RESTful endpoints for CRUD operations (e.g., /expenses, /expenses/:id).
* Controllers: Handles business logic for adding, updating, and deleting expense entries.
* Database: MongoDB database to store user expenses.
* Validation: Input validation ensures proper data formatting for expense records.

**Frontend**
* Components:
    * ExpenseTable: Displays expense entries in a paginated, sortable table.
    * Form: Allows users to add and edit expense details, with validation for 
      required fields.
    * Insights: Provides users with visual insights and financial predictions.
* State Management: React hooks (useState, useEffect) are used for efficient state handling.
* Navigation: React Router manages navigation between pages (e.g., dashboard, add expense, edit expense).
  
## Running Tests
To test API endpoints or other functionality, use tools like Postman or ThunderClient

## Features
* CRUD Operations: Add, edit, update, and delete expenses.
* Real-Time Updates: See your expenses update live as you manage them.
* Responsive Design: Works on desktop, tablet, and mobile devices.
* Financial Forecasting: Plan for future expenses and inflation impact.
* Data Validation: Form validation ensures that users input accurate and complete 
  information.
* Error Handling: Displays friendly error messages for users and detailed logs for 
  developers.

## Future Enhancements
* Authentication & Authorization: Secure user accounts and personalized expense 
  tracking.
* Data Export: Allow users to export expenses in CSV or PDF format.
* Advanced Filters: Enable filtering expenses by date range, category, or amount.
* Mobile App: Develop a mobile version of the app for iOS and Android.
* Multi-Currency Support: Support currency conversions for international users.
* AI-Powered Insights: Use AI to provide users with personalized financial advice.




