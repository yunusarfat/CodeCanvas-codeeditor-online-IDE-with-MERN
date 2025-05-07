# CodeCanvas: Online Code IDE with MERN Stack

CodeCanvas is an online code editor and development environment built with the MERN stack (MongoDB, Express, React, Node.js). It allows users to write, test, and execute code in a collaborative environment.

## Features

- **Real-time collaboration**: Multiple users can collaborate and edit code simultaneously.
- **Code execution**: Execute code in different languages directly from the editor.
- **Syntax highlighting**: Support for various programming languages with syntax highlighting.
- **Tailwind CSS integration**: Stylish, responsive UI using Tailwind CSS.
- **Monaco Editor**: Powerful editor with code suggestions, autocompletion, and more.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS, Monaco Editor
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**

## Installation

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) 
- [MongoDB](https://www.mongodb.com/) (or use MongoDB Atlas for cloud hosting)

### Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/yunusarfat/CodeCanvas-online-code-IDE-with-MERN.git
    cd CodeCanvas
    ```

2. Install backend dependencies:

    ```bash
    cd backend
    npm install
    ```

3. In the backend code, directly replace with your MongoDB connection string(like in models folder)
   

4. Run the backend server:

    ```bash
    npm start
    ```

5. Install frontend dependencies:

    ```bash
    cd frontend
    npm install --legacy-peer-deps
    ```

6. Run the frontend server:

    ```bash
    npm run dev
    ```

7. Visit the app at `http://localhost:3000`.

## Usage

1. Open the app in your browser.
2. Create an account or log in.
3. Start writing, editing, and executing code in the editor.
4. Collaborate with other users in real-time.

