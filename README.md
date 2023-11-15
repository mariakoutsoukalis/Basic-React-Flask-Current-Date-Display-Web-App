# React-Flask Date Display Application

This project demonstrates a simple integration of a React frontend with a Flask backend. The React app displays the current date retrieved from the Flask server.

## Features

- React frontend via Create-React-App for user interface.
- Flask backend server to provide the current date.
- Use of React hooks and state management.
- Fetch API to retrieve data from the Flask server.

## Installation

### Frontend

1. Ensure you have Node.js and npm installed.
2. Navigate to the frontend directory.
3. Install the dependencies:

```bash
npm install
```

### Backend

1. Ensure you have Python and Flask installed.
2. Navigate to the backend directory.
3. Install the required Python packages:

```bash
pipenv install flask
```

## Usage

### Running the Backend Server

1. Start the Flask server:

```bash
python3 app.py
```

### Running the Frontend Application

1. In a separate terminal, start the React application:

```bash
npm start
```

2. Open a web browser and visit `http://localhost:3000`.

## Understanding the Code

### Backend (Flask)

- The Flask app provides two endpoints: `/` returns a simple greeting, and `/date` returns the current date.
- The `get_viewable_date` function formats the current date for display.

### Frontend (React)

- The React app fetches the current date from the Flask server and displays it.
- Uses React hooks for state management and side effects.

## Customization

You can expand this project by adding more functionality to the React app or more endpoints to the Flask server.