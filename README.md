#WeLoveMovies

This project is part of the WeLoveMovies capstone, designed to build a RESTful API to manage movie-related data. The backend server is built using Express.js and Knex.js to interact with a SQL-based database.

Features
CRUD Operations: Manage movies, theaters, and reviews.
RESTful API: Follows REST design principles for routes and responses.
Database Management: Uses Knex.js to handle migrations, seeds, and queries.
Error Handling: Includes 404 error handling for non-existent routes and 405 for invalid methods.
CORS Support: Allows frontend requests through cross-origin resource sharing (CORS).


git clone https://github.com/your-username/welovemovies-api.git
cd welovemovies-api
Install dependencies:
npm install
Set up the database:
npx knex migrate:latest
npx knex seed:run
Start the server:
npm start
Testing
Run tests using the command:
npm test
Deployment
The backend can be deployed to platforms like Render or Heroku. Ensure proper configuration for your production environment and database.

#task 
All routes respond with appropriate status codes.
CORS is configured for frontend integration.
Database migrations and seeds are correctly configured and can be rolled back.
Deployed and working backend.
