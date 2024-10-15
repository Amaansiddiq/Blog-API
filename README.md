# Blog-API

A simple Blog API built with **Node.js** using a **RESTful API** architecture. This project allows for smooth interaction between two separate server instances: one for making requests and one for handling responses. The templating engine **EJS** is used for better integration of server-side data with the frontend.

## Features

- **Port 3000**: Handles all API requests via `server.js`.
- **Port 4000**: Handles API responses via `index.js`.
- **RESTful Architecture**: For efficient communication between the client and server.
- **EJS Templating**: Provides better integration of server-side data with HTML views.

## Prerequisites

To run this project locally, you need to have the following installed:

- **Node.js** (v14 or later)
- **npm** (Node Package Manager)

## Getting Started

Follow the steps below to set up the project on your local machine:

### Running the Servers

You need to run both `server.js` (for making requests) and `index.js` (for handling responses) on two separate ports.

#### To start the request-handling server (Port 3000):

```bash
node server.js
```

#### To start the response-handling server (Port 4000):

```bash
node index.js
```

Both servers will now be running on their respective ports, enabling seamless API communication.

## Project Structure

```
├── views/            # EJS files for templating
├── routes/           # API routes
├── server.js         # Handles API requests on port 3000
├── index.js          # Handles API responses on port 4000
├── package.json      # Project dependencies and scripts
└── README.md         # Project documentation
```

## Technologies Used

- **Node.js**: JavaScript runtime for building the server.
- **Express.js**: Web framework for Node.js to build the RESTful API.
- **EJS**: Embedded JavaScript templates for rendering HTML with data.
- **REST API**: Architecture for communication between client and server.

## Usage

After both servers are running, you can interact with the Blog API by making HTTP requests (GET, POST, PUT, DELETE) to the appropriate endpoints. The API will handle blog posts, comments, and other resources, returning responses based on the data stored in the backend.

## Contributing

Feel free to fork this repository and contribute improvements via pull requests. All contributions are welcome!
