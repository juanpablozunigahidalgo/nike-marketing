# Lead Software Engineer FullStack Technology Oregon
Develop a “Nike Product Inventory Management System” that enables Nike store managers to track, update, and analyse store inventories across different locations. This system should have a user-friendly front end for store managers and a secure, scalable back end for data management.
# Requirements
Frontend
Framework: React with TypeScript.

Functionality:
A login screen for store managers.
A dashboard showing a list of Nike products, inventory levels, and store location.
A search bar to filter products by name, category, or location.
An interface for updating inventory quantities, which triggers updates in the backend.
A chart showing inventory trends over time for a specific product.

Backend 
Framework: Express with TypeScript. 
Database: PostgreSQL, deployed using Docker. Cloud Storage: AWS S3 for storing product images. 
Containerization: Docker for backend services. API: User Authentication API (JWT-based). Product Inventory Management API, with routes for: Fetching all products and their details (name, category, stock level, image URL, etc.). Updating product inventory levels. Fetching product inventory trends. Image upload API for adding new product images. Environment: Environment variables to manage secrets and keys.

Cloud Setup
Hosting: Deploy the backend server on a cloud provider like AWS using AWS ECS (Elastic Container Service) for Docker.
Database: Deploy PostgreSQL on AWS RDS.
Storage: AWS S3 for product image storage.

Assignment Steps
Set Up Backend: Create a RESTful API using Express.js.
Configure Docker for containerizing the backend application.
Connect to a PostgreSQL database to store product data.
Configure AWS S3 to upload and serve images of products.
Implement routes for managing product inventory, updating stock levels, and authenticating users.
Implement a basic JWT-based authentication system.

Frontend Development:
Create a React application with TypeScript for the UI.
Build the UI components for the dashboard, inventory list, and trend charts.
Integrate with backend APIs for fetching product data, updating stock levels, and uploading images.
Use a library like Chart.js or D3.js to visualize inventory trends.

Cloud Deployment:
Use AWS ECS to deploy the backend container.
Deploy PostgreSQL on AWS RDS and connect it to the backend.
Set up AWS S3 for image storage and configure permissions.
Technical Requirements

Frontend:
React, TypeScript, CSS (or styled-components)
Axios or Fetch API for API requests

Backend:
Express with TypeScript
PostgreSQL for data storage
JWT for authentication
Docker for containerization

Cloud:
AWS ECS for deploying containers
AWS RDS for PostgreSQL database
AWS S3 for image storage

# Expected Deliverables
GitHub Repository: Share the code with clear documentation and setup instructions.
Deployment: Provide a link to the deployed backend and frontend.
Postman Collection: Include a Postman collection for testing the APIs.
Documentation:

# README: Detailed instructions on setting up and running the project.
API Documentation: Describe each API route, its request/response format, and authentication process.
Cloud Setup Guide: Basic steps to replicate the cloud setup.

# Bonus Points
Add data validation and error handling for inputs.
Use Redux for state management in the frontend.
Provide unit tests for both frontend and backend.
Include CI/CD setup for automated deployment.

