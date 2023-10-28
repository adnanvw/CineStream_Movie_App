# CineStream (MERN Movie)

<h5 align="center">A full-stack, open-source movie application built with MongoDB, Express, React, and Node.js (MERN stack).</h5>
<br/>

- [Configuration and Setup](#configuration-and-setup)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
  - [API](#api)
- [Author](#author)
- [License](#license)

## Configuration and Setup

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/adnanvw/CineStream_Movie_App.git
   ```

2. Open the project in your preferred code editor.

3. Navigate to the project directory and set up your development environment:

   - In one terminal, navigate to the client directory:

     ```bash
     cd client
     npm install # Install client-side dependencies
     npm start # Start the client
     ```

   - In another terminal, navigate to the server directory and configure environment variables in a .env file:

     ```env
     MONGODB_URL=your-mongodb-connection-string
     PORT=5000
     TOKEN_SECRET=your-secret-key
     TMDB_BASE_URL=your-tmdb-base-url
     TMDB_KEY=your-tmdb-api-key
     ```

     Then, install server-side dependencies and start the server:

     ```bash
     cd server
     npm install # Install server-side dependencies
     npm start # Start the server
     ```

4. Visit `http://localhost:3000` in your web browser to access CineStream.

## Key Features

- User registration and login
- Authentication using JWT Tokens
- Add favorites
- Delete favorites
- Leave reviews
- Delete reviews
- Password update
- Live search
- Watch trailers on YouTube
- 404 Page and more
- Skeleton loading effect
- Dark mode
- Responsive design

## Technologies Used

This project was created using the following technologies.

### Frontend

- React.js - JavaScript library for building user interfaces.
- React Hooks - For managing and centralizing application state.
- react-router-dom - To handle routing.
- axios - For making API calls.
- Material UI - For user interface components.
- CKEditor - Rich text editor.
- Formik - Form management and validation.
- React Redux - State management.
- React Toastify - To display interactive notifications.
- Swiper - For creating responsive and interactive sliders.

### Backend

- Node.js - Runtime environment for server applications.
- Express.js - Server framework for handling HTTP requests.
- Mongoose - For modeling and mapping MongoDB data.
- axios - For making API calls.
- jsonwebtoken - For authentication.
- cookie-parser - Middleware for handling cookies.
- cors - Middleware for enabling CORS.
- Dotenv - Module for loading environment variables.
- express-validator - For data validation.
- nodemon - Development utility for Node.js applications.

### Database

- MongoDB - NoSQL database used for storing collections.

### API

- TMDB API - Provides access to a database of movies, TV shows, and related information.

