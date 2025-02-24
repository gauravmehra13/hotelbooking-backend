# Backend for Hotel Booking Application (MongoDB, Express, Mongoose)

[![Node.js](https://img.shields.io/badge/node-%3E%3D14.0.0-green.svg)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com/)
[![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)](https://mongoosejs.com/)

This is a robust and scalable backend API built using Node.js, Express.js, MongoDB, and Mongoose. It provides a solid foundation for your web or mobile applications, offering efficient data management and seamless API interactions.

## Features

-   **MongoDB Integration:** Utilizes MongoDB for flexible and scalable data storage.
-   **Express.js Framework:** Leverages Express.js for fast and efficient routing and middleware.
-   **Mongoose ODM:** Employs Mongoose for elegant schema definitions and database interactions.
-   **RESTful API Design:** Follows RESTful principles for clear and intuitive API endpoints.
-   **Modular Structure:** Organized codebase for easy maintenance and scalability.
-   **Environment Variable Configuration:** Securely manages configuration using environment variables.

## Getting Started

### Prerequisites

-   Node.js (>= 14.0.0)
-   npm or yarn
-   MongoDB (local or cloud instance)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [repository-url]
    cd [project-directory]
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Configure environment variables:**

    Create a `.env` file in the root directory and add your environment variables. Example:

    ```
    PORT=8800
    MONGODB_URI=mongodb://localhost:27017/mydatabase
    # Add other necessary variables
    ```

    Replace `mongodb://localhost:27017/mydatabase` with your MongoDB connection string.

### Running the Application

This project includes two npm scripts for starting the server:

-   **`npm run dev`:** Starts the server using `nodemon`. This is ideal for development as it automatically restarts the server when changes are made to the code.
    ```bash
    npm run dev
    ```
    This command executes `"dev": "nodemon index.js"` from your `package.json`. `nodemon` watches your files and restarts your server upon file changes.
-   **`npm run start`:** Starts the server using `node`. This is intended for production environments.
    ```bash
    npm run start
    ```
    This command executes `"start": "node index.js"` from your `package.json`. It runs your `index.js` file directly with Node.js, without any automatic restarts.

### Project Structure
