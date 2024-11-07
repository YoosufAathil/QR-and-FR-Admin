# Backend README

## Project Overview

This project is the backend for the QR and FR Admin application. It provides the necessary APIs and services to support the frontend application.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- JWT for authentication
- Bcrypt for Hashing Password

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/QR-and-FR-Admin.git
    ```
2. Navigate to the backend directory:
    ```sh
    cd QR-and-FR-Admin/backend
    ```
3. Install dependencies:
    ```sh
    npm install
    ```

### Configuration

1. Create a `.env` file in the root of the backend directory and add the following environment variables:
    ```env
    PORT=5000
    MONGODB_URI=your_mongodb_uri
    FRONTEND_URL=your_frontend_url
    ```

### Running the Application

1. Start the server:
    ```sh
    npm start
    ```
2. The server will be running on `http://localhost:5000`.
