# ROXILER MERN Stack Coding Challenge

Welcome to the Roxiler MERN Stack coding challenge repository! This repository contains the source code for a web application developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It was created using Vite for efficient development.

## How to Use

To get started with this repository, follow the steps below:
1. **Navigate to the Project Directory**:

  ```
  cd .\Roxiler-Assignment\

  ```


2. **Install Dependencies**:
- For Backend (Node.js / Express.js):
  ```
  cd backend
  npm install
  ```
- For Frontend (React.js):
  ```
  cd frontend
  npm install
  ```


3. **Setup MongoDB Connection**:
- Create a `.env` file in the `backend` directory if it doesn't exist.
- Add your MongoDB connection string with username and password in the `.env` file:
  ```
  MONGODB_URL=your_mongodb_connection_string
  
  ```


4. **Set Backend URL in Frontend Environment file**:
- Create a `.env` file in the `frontend` directory if it doesn't exist.
- Add the backend URL in the `.env` file:
  ```
  VITE_BACKEND_URL=http://localhost:your_backend_port
  
  ```
  

5. **Run the Application**:
- Start the backend server:
  ```
  cd backend
  npm start
  ```
- Start the frontend development server:
  ```
  cd frontend
  npm run dev
  ```


6. **Access the Application**:
Once the servers are running, you can access the application by visiting `http://localhost:5173` in your web browser.

# THANK YOU
