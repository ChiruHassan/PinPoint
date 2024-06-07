# Pinterest Clone

This is a web application built with Node.js and Express that aims to replicate the core functionality of Pinterest, allowing users to create accounts, upload images of their favorite images.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Installation

1. Clone the repository:
git clone https://github.com/ChiruHassan/PinPoint.git
2. Navigate to the project directory
3. Install the dependencies: npm install
4. Set up the MongoDB database connection by modifying the `mongoose.connect` URL in the `user.js` file.
5. Start the development server: npm start || npx nodemon (if you have nodemon installed globally)

The application should now be running at `http://localhost:3000`.

## Usage

### Registration

1. Visit the homepage (`http://localhost:3000`).
2. Click on the "Don't have an account?" link.
3. Fill in the registration form with your details (username, email, password, etc.).
4. Click the "Register" button to create your account.

### Login

1. Visit the homepage (`http://localhost:3000`).
2. Enter your username and password.
3. Click the "Login" button to access your profile.

### Uploading Images

1. After logging in, click on the "Add" button in the navigation bar.
2. Upload an image by clicking the "Choose File" button.
3. Enter a title and description for the image.
4. Click the "Create Post" button to save the image.

### Viewing Posts

1. After logging in, you can view all your uploaded images on the "Profile" page.
2. The "Feed" page displays posts from all users.

## Features

- User authentication (registration, login, logout)
- Image uploads with validation
- Create and view user posts
- Global feed displaying posts from all users

## Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript) for templating
- MongoDB (with Mongoose ODM)
- Passport.js for authentication
- Multer for file uploads
- Tailwind CSS for styling
