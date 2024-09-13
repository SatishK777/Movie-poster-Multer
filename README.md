# Movie Management System with Image Upload

## Project Description

The Movie Management System is a CRUD (Create, Read, Update, Delete) web application designed to manage a collection of movies. Users can add new movies, view a list of all movies with their posters, edit movie details, and delete movies from the database. The application uses Node.js, Express.js, MongoDB, EJS, and Multer to handle movie data and image uploads.

## Features

- **Add Movie**: Users can add new movies by providing information such as the movie title, description, release date, genre, rating, and uploading a movie poster.
- **View Movies**: Displays a list of all movies in the database, including their posters and details.
- **Edit Movie**: Users can update movie details, including uploading a new poster if needed.
- **Delete Movie**: Allows users to delete a movie and its associated poster from the database.

## Technologies Used

- **Backend**: Node.js and Express.js for server-side logic and handling HTTP requests.
- **Frontend**: EJS (Embedded JavaScript) for rendering dynamic HTML pages.
- **Database**: MongoDB for storing and managing movie data.
- **File Upload**: Multer for handling image uploads, allowing users to upload movie posters.

## Project Workflow

1. **Home Page**: Displays a list of all movies with their posters.
2. **Add Movie Page**: A form to input new movie details, including an option to upload a poster image.
3. **Edit Movie Page**: A form pre-filled with movie details, allowing users to update information and change the poster image if needed.
4. **Delete Movie**: A button to delete a movie and its associated poster directly from the list.

## Routes

- **GET /movies**: Display all movies with their posters.
- **GET /movies/add**: Display the form for adding a new movie, including an option to upload a poster.
- **POST /movies**: Handle adding a new movie and poster image to the database.
- **GET /movies/edit/:id**: Display the form for editing an existing movie, with an option to upload a new poster.
- **POST /movies/update/:id**: Handle updating an existing movie and replacing the poster if needed.
- **GET /movies/delete/:id**: Handle deleting a movie and its poster from the database.

## Multer Integration

- **Multer Setup**: Configured Multer to handle file uploads and store uploaded poster images in a designated folder on the server.
- **File Storage**: Set up proper storage for the uploaded files, with unique naming to avoid conflicts.

## Learning Outcomes

- Implementing CRUD operations using Node.js, Express.js, and MongoDB.
- Handling image uploads using Multer in a Node.js application.
- Connecting and performing operations on a MongoDB database.
- Rendering dynamic pages using EJS.
- Managing file uploads and handling file storage on the server.
