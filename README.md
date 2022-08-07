WeLoveMovies

Built using Express, PostSQL, and Knex
To Run Server
1. Fork / clone this repo
2. cd into project folder
3. Run npm install to install project dependencies.
4. Run npm run start:dev to start your server in development mode.
5. Or, run npm start.
Endpoints to Test
GET /movies/?is_showing=true for movies currently in theaters.
GET /movies/21 for details on "Spider-Man: Into the Spider-Verse"
GET /movies/210 for an error response for a movie id that does not exist
GET /movies/21/reviews for reviews of a movie
delete a review by using it's review_id which you can find an example of in the response from the previous request. DELETE /reviews/141, for example.
GET /theaters for list of all theaters
 
