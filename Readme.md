**Chat App Setup Guide**
This guide will help you set up the Chat App locally on your machine. 
Please follow the steps below.

**1. Clone the Repository**
Start by cloning the repository to your local machine:
git clone https://github.com/Varad-01/Chat-App.git

After cloning, navigate to the project directory:
cd Chat-App


**2. Configure Environment Variables**
**Backend Configuration**
Inside the backend folder, create a .env file.
Add the following environment variables to the .env file:
JWT_SECRET=abc
JWT_LIFETIME=abc
MONGODB_URI=abc

**Frontend Configuration**
Inside the frontend folder, create a .env file.
Add the following URL to the .env file:
REACT_APP_URL=http://localhost:4000


**3. Install Dependencies**
You need to install the required dependencies for both the backend and frontend.
Backend: In the backend directory, run:
npm install

Frontend: In the frontend directory, run:
npm install


**4. Start the Application**
Backend
Navigate to the backend folder.

Use nodemon to start the backend server:
nodemon index.js

This will start the backend server on http://localhost:5000.

Frontend
Navigate to the frontend folder.
Start the frontend application:
npm start
This will start the frontend server on http://localhost:3000.

**5. Application Running**
The backend API will run on: http://localhost:5000
The frontend React app will run on: http://localhost:3000
You can now interact with the Chat App in your browser.

