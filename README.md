# Expense Tracker Application (MERN Stack)

This is a full-stack Expense Tracker application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to track their expenses dynamically, with data stored in MongoDB, and provides an interactive and responsive interface through React.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Environment Variables](#environment-variables)
- [File Structure](#file-structure)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Features
- Add, edit, and delete expenses.
- Categorize expenses.
- View total expenses and filter by date.
- Responsive design for mobile and desktop.

## Technologies
- **MongoDB**: NoSQL database for storing expense data.
- **Express.js**: Backend framework for building APIs.
- **React.js**: Frontend library for creating user interfaces.
- **Node.js**: JavaScript runtime for backend.
- **CORS**: To handle cross-origin requests.
- **dotenv**: To manage environment variables.

## Getting Started

### Prerequisites
- Node.js installed on your local machine.
- MongoDB setup locally or MongoDB Atlas for a cloud database.
- A package manager like npm or yarn.

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/expense-tracker-mern.git
    cd expense-tracker-mern
    ```

2. Install backend dependencies:
    ```bash
    cd backend
    npm install
    ```

3. Set up MongoDB by configuring your `.env` file (see below for the structure).

4. Start the backend server:
    ```bash
    npm start
    ```

The backend server should be running at `http://localhost:5000`.

### Frontend Setup

1. Navigate to the `frontend` directory and install the dependencies:
    ```bash
    cd ../frontend
    npm install
    ```

2. Start the React development server:
    ```bash
    npm start
    ```

The frontend will be running at `http://localhost:3000`.

## Environment Variables

Create a `.env` file in the backend root and add the following environment variables:

