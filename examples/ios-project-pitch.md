# Balloonicorn - My Media Database

An app to allow users to search for and track their favorite movies, tv shows, and books.

## Background

While there are many great applications out there to track individual media items (ex. Goodreads lets users track their favorite books), there are not any great applications for tracking a combination of your favorite book, movies, and tv shows.

## MVP

- As a user, I want to be able to search for movies, tv shows, and books.
- As a user, I want to be able to create categories to save my content in.
- As a user, I want to be able to add individual items to a category of my choosing.
- As a user, I want to be able to add the following metadata for each item: title, author/director, release/published year, length, description, and notes.
- As a user, I want to be able to favorite items.
- As a user, I want to be able to access my favorite items by clicking on a favorites category.

## Tech stack

- Swift
- SwiftUI
- CoreData
- URLSession

### Dependencies

- TMDB API
- Goodreads API

## Roadmap

### Sprint 1

- Create models
- Create view templates
- Add functionality for a user to pull data from TMDB and Goodreads APIs and display it

### Sprint 2

- Add functionality for user to create categories
- Add functionality to save searched items into a category
- Add functionality to favorite an item and add it to a favorited category
- Add functionality to allow a user to add their own notes to a saved item

### Sprint 3

- Do extensive testing and fix any bugs
- Add custom styling to the application
- Create video demo of application
