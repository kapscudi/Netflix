# Movie Surfing application

- Movie Surfing application made using React, Redux ,NodeJS, Express and MongoDB 

---

## Quick Links

- [Vedio Walkthrough](#VedioWalkthrough)

- [Stack Used](#stack-used)

- [About](#about)
 
- [Features](#Features)

- [Running Projects Locally](#running-projects-locally)
   - [Front END](#front-end)
   - [SERVER](#server)


- [TODO](#todo)

- [Author](#author)

---

## VedioWalkthrough

### Live Site Demo

Demo: 

### Video Demo

---

## Stack Used

- React
- Redux
    - State management and redux thunk for asynchronous api calls
- ReactHooks   
- NodeJS
   - Backend and database with node and mongoDB
- ExpressJS
- Axios
- MongoDB
    -For database
- [TMDB API](https://www.themoviedb.org/?language=en-US)
  - Movie Database API for fetching movies and trailers.
-  React Router-Dom
   - Used for Complex and dynamic route creations and redirections
- [React Reveal](https://www.react-reveal.com/)
- Node Mailer
  - To send varification emails
 -Sass 
  - For fast and powerfull styling
 - Media Queries
   - For responsiveness
 

---

## About
A full functional movie application( highly inspired by netflix) made with advanced React, Redux ,Node, Express, MongoDB and Axios.It uses redux thunk to asynchronously fetch movie data from Tmdb api, which contains more than 30 thousand movies in its database. 

## :heavy_check_mark: Features:
- Interactive UI replication from the very original, NETFLIX.
- Responsive
- Login with forget password feature, Register with email verification (JWT token based).
- Protected user Sign Up, Signin and Signout.
- Signing in Using google.
- Reset Password Option for the users.
- Add to favourites option for each user.
- All Trailer links to the Youtube.
- Dynamically generated movie and tv show description page.
- A flexible and active searchbar.




### User Stories

- Users can safely Sign up and Sign in through email or Google, according to their preference.
- A searchbar to search through any movie from the TMDB database (which contain over 30 thousand movies).
- Large collections of popular movies and tvshows for them to binge on.
- Movie and TV-show pages dynamically generated for every single movie.
- Details of movies or Tv shows include imdb rating, cast info, link to the official trailers.
- Add to favourite with one click any movie or tvshow to watch later.
- Original Netflix UI replicated with advanced and highly organized sass and css styling.
- Full responsive experience for user.

## Running Projects Locally
 # Front End

- To try locally create a file ".env" in the root of the client folder and add the needed env variables.
   - REACT_APP_API= http://localhost:8000/api
- Then execute npm start (make sure the server and database part is up and  running).
- Install dependencies: run `npm install` in root project
- Get API key from [here](https://www.themoviedb.org/documentation/api)
- Create .env file in root project and add: `API_KEY=YOUR_API_KEY_HERE`
- Run project: `npm start`

# Server
- Start mongoDB
- Create ".env" file in th root of server folder and add 
   - PORT= 8000
   - CLIENT_URL= http://localhost:3000
   - DATABASE = your database url
   - JWT_SECRET= You can use any random collection
   - JWT_ACCOUNT_ACTIVATION= You can use any random collection
   - JWT_RESET_PASSWORD= You can use any random collection
- Configure node mailer
- Type " npm install " inside the root directory (To download server/back-end dependencies)
- To run use "npm start"

### TODO
- To Create user profile page.
- Filter by genre.
- Booking option for available movies.

---

## Author

- TANEA JOSHI 

---
Please feel free to create a pull request or submit any issues!
