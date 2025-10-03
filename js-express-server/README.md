# JavaScript Express Server

This project is a simple Express server application that listens on port 8001. It is designed for development with automatic code reloading using Nodemon.

## Project Structure

```
js-express-server
├── src
│   └── index.js         # Entry point of the application
├── package.json         # NPM configuration file
├── Dockerfile           # Dockerfile to build the application image
├── .gitignore           # Files and directories to be ignored by Git
├── .env                 # Environment variables for the application
└── README.md            # Project documentation
```

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- Docker installed on your machine (if you want to run the application in a container).

### Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd js-express-server
   ```

2. Install dependencies:

   ```
   npm install
   ```

### Running the Server

To start the server with automatic reloading, use the following command:

```
npm run dev
```

This will start the server on `http://localhost:8001`.

### Running with Docker

To build and run the application using Docker, use the following commands:

1. Build the Docker image:

   ```
   docker build -t js-express-server .
   ```

2. Run the Docker container:

   ```
   docker run -p 8001:8001 js-express-server
   ```

The server will be accessible at `http://localhost:8001`.

### License

This project is licensed under the MIT License.