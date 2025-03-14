# Notes Application

A full-stack notes application featuring an Express.js backend and a Vite-powered React frontend.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Backend**: Provides RESTful API endpoints to manage notes.
- **Frontend**: Allows users to view, add, and delete notes with a responsive interface.

## Project Structure

```
notes-application/
├── backend/
│   ├── index.js        # Express.js server
│   └── package.json    # Backend dependencies
└── frontend/
    ├── src/
    │   ├── components/ # React components
    │   ├── App.jsx     # Main React component
    │   └── main.jsx    # Entry point
    └── package.json    # Frontend dependencies
```

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/notes-application.git
   cd notes-application
   ```

2. **Install Backend Dependencies**:

   Navigate to the backend directory and install the necessary packages:

   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**:

   Navigate to the frontend directory and install the necessary packages:

   ```bash
   cd ../frontend
   npm install
   ```

## Running the Application

1. **Start the Backend Server**:

   In the backend directory, start the Express.js server:

   ```bash
   npm start
   ```

   The server will run on http://localhost:3001.

2. **Start the Frontend Development Server**:

   In the frontend directory, start the Vite development server:

   ```bash
   npm run dev
   ```

   The application will be accessible at http://localhost:5173.

## API Endpoints

- `GET /`: Returns a welcome message.
- `GET /api/notes`: Retrieves all notes.
- `GET /api/notes/:id`: Retrieves a note by its ID.
- `POST /api/notes`: Adds a new note.
- `DELETE /api/notes/:id`: Deletes a note by its ID.

## Technologies Used

**Backend**:
- Express.js: Web framework for Node.js.
- CORS: Middleware for enabling CORS.

**Frontend**:
- React: JavaScript library for building user interfaces.
- Vite: Next-generation frontend tooling.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
