
# Stitch: Realtime Collaborative Editor

Stitch is a real-time collaborative code editor built with React and Node.js, leveraging Socket.io for instant communication. It allows multiple users to edit the same document simultaneously, with changes reflected across all connected clients in real-time.

## Features

*   **Real-time Collaboration**: Multiple users can edit code concurrently.
*   **CodeMirror Integration**: Provides a rich and extensible code editing experience.
*   **Instant Updates**: Changes are broadcasted and synchronized across all connected clients.

## Technologies Used

*   **Frontend**:
    *   React.js
    *   React Router DOM
    *   Socket.io Client
    *   CodeMirror
    *   React Hot Toast (for notifications)
    *   React Avatar (for user avatars)
*   **Backend**:
    *   Node.js
    *   Express.js
    *   Socket.io
    *   Nodemon (for development server auto-restarts)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed:

*   [Node.js](https://nodejs.org/en/) (which includes npm)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository_url> # Replace <repository_url> with your actual repository URL
    cd stitch
    ```

2.  **Install dependencies:**

    Navigate to the project's root directory and install both frontend and backend dependencies:

    ```bash
    npm install
    ```

## Running the Project

The project consists of a frontend (React) and a backend (Node.js/Express). You'll need to run both concurrently for the application to function correctly.

### Development Mode

For development, you can run the frontend and backend separately with hot-reloading.

1.  **Start the Frontend Development Server:**

    Open your first terminal window, navigate to the project root, and run:

    ```bash
    npm run start:front
    ```

    This will start the React development server, usually accessible at `http://localhost:3000`.

2.  **Start the Backend Development Server:**

    Open a second terminal window, navigate to the project root, and run:

    ```bash
    npm run server:dev
    ```

    This will start the Node.js backend server using `nodemon`, which will automatically restart the server when you make changes to the backend code. The backend typically runs on `http://localhost:5000` (or another port if configured differently).

### Production Mode

To build the frontend for production and run the backend in a production environment:

1.  **Build the Frontend:**

    ```bash
    npm run build
    ```

    This command compiles the React application into static files in the `build` directory.

2.  **Start the Production Server:**

    ```bash
    npm run server:prod
    ```

    This command will serve the built frontend files and run the Node.js backend.

## Available Scripts

In the project directory, you can run:

*   `npm start`: Builds the frontend for production and then starts the production Node.js server.
*   `npm run start:front`: Starts the React development server.
*   `npm run build`: Builds the app for production to the `build` folder.
*   `npm run server:dev`: Starts the Node.js backend server in development mode with `nodemon`.
*   `npm run server:prod`: Starts the Node.js backend server in production mode.
*   `npm test`: Launches the test runner in the interactive watch mode.
*   `npm run eject`: Removes the single build dependency from your project.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.