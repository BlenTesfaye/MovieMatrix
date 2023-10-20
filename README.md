# Studio Ghibli DB  - (an online movie-database) -


## Project Overview
This Movie Database App aims to create a user-friendly platform for users to explore and interact with movie information. Users can view movie details, leave reviews and ratings and explore their intrests.

Key Features
-The following are key features for the MOVIEMATRIX App:

  ## Movie Listings:
- Display a list of movies with basic details, including title, release year, director, and genre.
  ## Search and Filtering:
- find movies by title or genre.
- Allow basic sorting options.
  ## Review and Rating System:
- Allow users to leave text-based reviews and numerical ratings for movies.
  ## User Management: 
- Enable user to access app with a username/ name authorization. have ability to display interests

## wireframe 

![Image 10-20-23 at 9 35 AM](https://github.com/BlenTesfaye/MovieMatrix/assets/143666820/b2b609a3-30a0-4db2-b027-e4238c9825a2)

--------------------------------------------------------------------------------------------------------------------------------------
## ERD 
### ![Image 10-20-23 at 9 38 AM](https://github.com/BlenTesfaye/MovieMatrix/assets/143666820/1bb868ed-85b1-4eec-8611-7e8a5f6d2d40)
for movies model, users model, and reviews and ratings model: 


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
Each movie can have multiple reviews and ratings by users.

## Users Model:

Attributes:
- Username (string): The username of the user.
- Email (string): The email address of the user. (optional)
- user intrests (string or array):a feild to strore user interests. (database schema)  

Relationships:
One-to-Many with Reviews and Ratings Model: Each user can create multiple reviews and ratings.

## Reviews and Ratings Model:

Attributes:
- Review Text (string): The text of the movie review.
- Rating (number): The numerical rating given to the movie.

## Relationships:
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
- External APIs: for Integrating external movie data APIs (e.g. Omdb) for database to have detailed movie information, images, and trailers.
- Advanced Search and Filters: Enhance the search and filtering options with additional criteria, such as release year, cast, or advanced genre options.
- Advanced Search and Filters: Enhances the search and filtering options with additional criteria, such as release year, cast, or advanced genre options. (think LetterBoxd)




