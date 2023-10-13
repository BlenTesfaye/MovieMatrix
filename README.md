# MovieMAtrix - (an online movie-database) -

## Project Overview
This Movie Database App aims to create a user-friendly platform for users to explore and interact with movie information. Users can view movie details and leave reviews and ratings.

Key Features
-The following are key features for the online Movie Database App:

## Movie Listings:
-Display a list of movies with basic details, including title, release year, director, and genre.

## Search and Filtering:
-Implement search functionality to find movies by title or genre.
-Allow basic sorting options.

## Review and Rating System:
- Allow users to leave text-based reviews and numerical ratings for movies.
  
## User Management: 
-Enable user registration with a username. authentication and authorization for secure access to the app.
--------------------------------------------------------------------------------------------------------------------------------------
## ERD 
### for movies model, users model, and reviews and ratings model: 

## Movies Model:

Attributes:
- Title (string): The title of the movie.
- Release Year (number): The year the movie was released.
- Director (string): The director of the movie.
- Genre (string): The genre of the movie.
- Description (string): A brief description of the movie.
- Poster URL (string): The URL of the movie's poster image.
Relationships:
One-to-Many with Reviews and Ratings Model:
Each movie can have multiple reviews and ratings.

## Users Model:

Attributes:
- Username (string): The username of the user.
- Email (string): The email address of the user. (optional)
- Password (string): The hashed password of the user.

Relationships:
One-to-Many with Reviews and Ratings Model: Each user can create multiple reviews and ratings.

## Reviews and Ratings Model:

Attributes:
- Review Text (string): The text of the movie review.
- Rating (number): The numerical rating given to the movie.

Relationships:
Many-to-One with Movies Model: Each review and rating is associated with a single movie.
Many-to-One with Users Model: Each review and rating is created by a single user
---------------------------------------------------------------------------------------------------------------------------
### MVP and Stretch Goals 

# MVP: 
* Basic Movie Listings: includes interface to display a list of movies with essential details like title, release year, director, and genre.

* Search and Filtering: a functionality that allows users to find movies by title and filtering options like genre. (allow users to explore the database.)

* Review and Rating System:  allows users to leave text-based reviews and numerical ratings for movies.

* User Registration: for users who want to leave reviews. 


# Stretch goals: 

- User Interaction: Allow users to comment on reviews and like/favorite movies. This adds a social aspect to the application.
- External APIs: for Integrating external movie data APIs (e.g. IMDB) for database to have detailed movie information, images, and trailers.
- Advanced Search and Filters: Enhance the search and filtering options with additional criteria, such as release year, cast, or advanced genre options.
- Advanced Search and Filters: Enhances the search and filtering options with additional criteria, such as release year, cast, or advanced genre options. (think LetterBoxd)




