# Assignment 1 - ReactJS app.

Name: John O'Mahony (20098626)

## Overview.

This a React App that uses TMDB(The Movie Database) API Key to call over information from this website, and display it in my react app that I created.

### Features.

+ New Trending Movies Page
+ New Top Rated Movies page
+ Updated Homepage
+ New Similar Movies Page
+ Movie Actors Page and Move Actors Details Page
+ Movies are linked to specific actors
+ New Movie Actors Filter
+ Login and SignUp Page Added
+ An attempt Private Routes added to Movies favorites page

## Setup requirements.

clone the repoository
create a .env file in movies-api with the following contents:
NODE_ENV=development
PORT=8080
HOST=localhost
MONGO_DB=mongodb+srv://20098626:127mountains@johnmovies.zjj4cvn.mongodb.net/movies?retryWrites=true&w=majority
TMDB_KEY= [Your API key from TMDB]
SECRET= [your own secret e.g. ilikecake]

## API endpoints.

+ movies/trending -  A list of trending movies
+ movies/:id/similar - A list of similar movies based on a specifc movie
+ movies/toprated -  A list of the top rated movies of all time
+ movies/now-playing - A list of movies that are now playing in cinemas
+ actors/ - A list of movie actors
+ actors/:id - A Actor details page, including their specific filmogrophy
+ page=:pageNumber - Used for pagination on the Discover Movies page
+ users/signup - A sign up form
+ users/login - A login Form(Attempted Using Authenication from Firebase)

## Routing.

+ movies/trending - Displays a movies page with trending movies
+ movies/:id/similar - Displays a page of similar movies to a certain movie
+ movies/toprated - Displays a list of top rated movies of all time
+ movies/now-playing - Displays a list of movies playing now in cinemas
+ actors/ - Displays a list of popular movie actors
+ actors/:id - Displays a page with actor details and the movies they are in (filmogrophy)
+ users/signup - Displays a Signup page
+ users/login - Displays a Login Page




## Independent learning (If relevant).

Firebase - https://firebase.google.com/docs?gclid=CjwKCAiAksyNBhAPEiwAlDBeLFmJbo_e3-ogmR35UAUMkE9IIanL7VSwEQbkimCxlwelRP1Ae2hmqBoC1H8QAvD_BwE&gclsrc=aw.ds

https://firebase.google.com/docs/web/setup

Pagination - https://mui.com/material-ui/react-pagination/

https://hygraph.com/blog/react-pagination
