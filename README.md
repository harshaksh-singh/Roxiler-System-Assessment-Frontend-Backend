# Roxiler-System-Assessment-Frontend-Backend
Built to showcase skills in both backend and frontend development.
Roxiler System Assessment - MERN Stack Project
Backend Tasks
Data Source
Third-party API URL:  https://s3.amazonaws.com/roxiler.com/product_transaction.json
Request Method: GET
Response Format: JSON
APIs to Develop
Database Initialization

Fetch data from the third-party API.
Populate the database with this seed data using an efficient table/collection structure.
Transactions List API

Retrieve transactions for a given month (January to December).
Support:
Search: Match input text in fields like title, description, or price.
Pagination: Default values: page = 1, per page = 10.
Statistics API

Provide:
Total sales amount for the selected month.
Total number of sold and unsold items for the selected month.
Bar Chart API

Return item counts within predefined price ranges for the selected month, such as:
0–100, 101–200, 201–300, ..., 901-above.
Pie Chart API

Provide unique product categories and the count of items in each category for the selected month.
Example:
Category X: 20 items
Category Y: 5 items
Category Z: 3 items
Combined Data API

Combine the results of the above APIs into a unified response.
Frontend Tasks
Features to Implement
Transactions Table

Use the transactions listing API to display a paginated and searchable table.
Include a dropdown for selecting months (January–December), defaulting to March.
Search input should dynamically filter results based on title, description, or price.
Pagination should load next/previous pages via API calls.
Statistics Box

Display:
Total sales amount.
Total sold and unsold items for the selected month.
Bar Chart

Show price ranges and the corresponding number of items for the selected month.
Pie Chart

Display categories and the count of items in each for the selected month.
Project Setup Instructions
Prerequisites
Node.js installed.
MongoDB installed and running locally.
Backend Setup
Navigate to the backend folder:
bash
Copy code
cd backend
Install dependencies:
bash
Copy code
npm install
Start the server:
bash
Copy code
npm start
Frontend Setup
Navigate to the frontend folder:
bash
Copy code
cd frontend
Install dependencies:
bash
Copy code
npm install
Start the development server:
bash
Copy code
npm start
Acknowledgment
This project demonstrates a MERN stack implementation for handling APIs, database management, and frontend visualization.
