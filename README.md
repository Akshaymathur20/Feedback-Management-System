# Project Overview

This project is a simple feedback management system consisting of a backend server built with Node.js, Express, and TypeScript, and a frontend application built with React and TypeScript. The system allows users to submit feedback and view a list of all feedback entries.


# Project Structure

# Frontend

The frontend is a React application that provides a form for submitting feedback and a list to display all feedback entries. It communicates with the backend API using Axios.
![Frontend](https://github.com/Akshaymathur20/Feedback-Management-System/assets/80681817/80c337e8-936b-4051-a1ba-97e8f1515a71)


# Backened

The backend is responsible for handling API requests and storing feedback entries in an in-memory data structure. It is built using Node.js, Express, and TypeScript. No external in-memory storage solutions like Redis are used.

![backend](https://github.com/Akshaymathur20/Feedback-Management-System/assets/80681817/7afcfe38-adc9-4a9c-bf51-4b61dc6b2bac)

Endpoints:

GET /feedback: Retrieve all feedback entries.
POST /feedback: Submit new feedback. The request body should contain { name: string, feedback: string }.



# Setup and Installation

 Clone the repo
   ```sh
   git clone https://github.com/Akshaymathur20/Feedback-Management-System.git
   ```
Navigate to the backend directory:

cd backend
Install dependencies:

```sh
npm install
```

Start the backend server:
```sh
npx ts-node src/index.ts
```


The backend server will be running on http://localhost:5000.

Navigate to the backend directory:

cd frontened
Install dependencies:
```sh
npm install
```
```sh
npm start
```

The frontened application will be running on 'http://localhost:3000'.



