🚀 This repository contains a Node.js application with a React client. The Node.js application includes a ⚡ Redis cache implementation with Mongoose, allowing for lightning-fast data access by storing it in memory. The code includes advanced functions for setting and getting cache values, with options for setting expiration times. Use this cache implementation to turbocharge the performance of your frequently accessed data applications.

💅 The React client is built using 💅 styled-components, 🎨 Twin.macro, and 🌈 Tailwind CSS, making it easy to style and customize your user interface.

# Prerequisites

Before you can run the application, you need to set the following environment variables:

## Server-Side Environment Variables

In the root directory of the project, create a .env file with the following environment variables:

    # PORT
    PORT=<your-port>

    # MongoDB URI
    MONGOURI=<your-mongodb-uri>

    # Redis
    REDIS_HOST=<your-redis-host>
    REDIS_PORT=<your-redis-port>

## Client-Side Environment Variables

In the Client directory, create a .env file with the following environment variable:

    # Backend Endpoint
    REACT_APP_API_ENDPOINT=<your-backend-endpoint>

# Installation

To install the dependencies for the entire project, run npm install in the root directory of the project:

    cd <repository-name>
    npm install

Then, navigate to the Client directory and run npm install again to install the client dependencies:

    cd Client
    npm install

# Usage

To run the application, start the Node.js server in the root directory of the project:

    cd Client
    npm start

# Technologies Used

- Node.js - Server-side runtime environment
- Express - Web application framework for Node.js
- Mongoose - Object Data Modeling (ODM) library for MongoDB and Node.js
- Redis - In-memory data structure store
- React - JavaScript library for building user interfaces
- Styled Components - CSS-in-JS styling library for React
- Twin.macro - Tailwind CSS-in-JS library for styled-components
- Tailwind CSS - Utility-first CSS framework

Thank you for checking out this Node.js application with a React client. If you have any questions, feedback, or suggestions, please feel free to reach out to me at [Rohit Chavan](mailto:rohitchavan110116114@gmail.com?subject=RedNode%20Application) and let me know. Happy coding! 😊
