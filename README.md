
# ALX Project 0x14

## API Overview
The MoviesDatabase API provides access to a large collection of movie data, including details about movies, actors, directors, and genres. You can search for movies, get trending titles, and retrieve detailed information for each movie. The API is designed for developers to easily integrate movie-related data into their applications.

## Version
v1.0
*(Replace with the actual version from the API documentation if different)*

## Available Endpoints
- `/movies` – Retrieve a list of movies.
- `/movies/{id}` – Get details for a specific movie by ID.
- `/actors` – Retrieve a list of actors.
- `/actors/{id}` – Get details for a specific actor by ID.
- `/search` – Search for movies by title, actor, or genre.
- `/trending` – Retrieve trending movies for the week.

## Request and Response Format

### Example Request
```http
GET https://api.moviesdatabase.com/movies
Headers:
  Authorization: Bearer YOUR_API_KEY
