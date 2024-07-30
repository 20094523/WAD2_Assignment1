# Assignment 1 - ReactJS app.

Name: Dominik Martynski

## Overview.

This repository contains an extended version of the movies app created in the labs. 
I have added a latest, watchlist and trending pages along with parametized endpoints
for each with their own seperate details.

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]
 
+ All lab work complete e.g. production countries showing up, adding to watchlist working.
+ Watchlater page created, displaying movies in the same way favorites did.
+ Actors added to moviesinfo.
+ Got recommended movies working.
+ Alternative titles for each movie displaying.
+ A new UI element list and listitems was used on movieDetails.
+ A new page displaying most popular movies.


## Setup requirements.

No additional set-up steps necessary. Clone repo onto machine, add your TMDB api key to .env, npm install and npm run.

## API endpoints.

+ Movie recommendations - /movie/:id/recommendations
+ Upcoming movies - /movie/watchlaterpage
+ Alternative titles - /movie/:id/alternative_titles
+ Popular movies - /movie/popular

## Routing.

+ Movie recommendations - /movies/:id/recommendations
+ Upcoming movies - /movies/watchlaterpage
+ Recommended movies - /movies/:id/recommended
+ Popular movies - /movies/popular
