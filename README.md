



## Project Description

**Project Name:** Online Learning Platform using MERN

This online learning platform is designed to enhance student engagement and facilitate instructor-student interaction through a user-friendly, feature-rich web interface. It includes features like course enrollment, access to educational content, forum discussions, and profile management. This web app is built with the MERN stack, ensuring a seamless user experience and efficient data management.


## Steps to Run the Application Locally

Follow these steps to set up the application on your local machine

### 1. Clone the Repository

### 2. Navigate to the cloned repository

```bash 
    cd online-learning-platform
```

### 3. Configuration Settings
Rename the environment file in the client side.
```bash
    Rename .env.local to .env.local
```

### 4. Setting up the frontend
Open a new terminal in VS Code and run the following commands to install the required packages and start the frontend

```bash
    cd Client
    npm install   # install the required packages
    npm run dev
```
Open a browser and navigate to http://localhost:5173 to access the frontend of the application.

### 5. Setting up the backend
Open another terminal in VS Code and run the following commands to install the necessary packages and start the backend server

```bash 
    cd server
    npm install      # install the required packages
    node server.js   # or use nodemon for automatic restarts with `nodemon server.js`
```
The backend server will start on **PORT 5000** by default. You can adjust this setting in the .env file if needed.

---

## Technologies Used

- **Frontend**: React, HTML, CSS, JavaScript, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Environment Management**: dotenv

---

## Additional Information

For further assistance or doubts, reach out to any team member listed above or find their GitHub ID from the collaborators list.

---
