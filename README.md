# Auction Platform Site
 
## Overview
This is a full-stack web application that allows users to participate in an online bidding system. The application includes user authentication, auction item listing, bidding functionality, and a user-friendly interface for managing and viewing bids.

## Features
- User registration and authentication
- Auction item management (create, view, update, delete)
- Bidding functionality with bid history
- User profile management

## Tech Stack
- Frontend: React
- Backend: Node.js, Express
- Database: MongoDB with Mongoose
- Authentication: JWT
- API Documentation: Swagger

## Prerequisites
- Node.js
- MongoDB
- npm 

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd auction-platform
2.	Install dependencies for server
bash
Copy code
cd server
npm install
3.	Set up environment variables Create a .env file in the server directory and add the following:
env
Copy code
MONGO_URI=mongodb://localhost:27017/auction-platform
JWT_SECRET=your_jwt_secret
4.	Start the server
bash
Copy code
npm start
5.	Install dependencies for client
bash
Copy code
cd ../client
npm install
6.	Start the client
bash
Copy code
npm start
7.	Access the application Open your browser and go to http://localhost:3000 for the server and http://localhost:3001 for the client.
![image](https://github.com/user-attachments/assets/b1d19c2f-d177-49a9-af52-a895593e8843)
