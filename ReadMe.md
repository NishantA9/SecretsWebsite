Secrets Project

This application allows users to register, log in, and submit and view their secrets anonymously. It's built using Express, PostgreSQL, Passport.js, bcrypt for hashing passwords, and Google OAuth for authentication.

Run the Sql Queries 
Create a .env and then paste these

        GOOGLE_CLIENT_ID="YOUR_GOOGLE_CLIENT_ID"
        GOOGLE_CLIENT_SECRET="YOUR_GOOGLE_CLIENT_SECRET"
        SESSION_SECRET="YOUR_SESSION_SECRET"
        PG_USER="postgres"
        PG_HOST="localhost"
        PG_DATABASE="secrets"
        PG_PASSWORD="YOUR_PG_PASSWORD"
        PG_PORT="5432"

run npm i and then npm i nodemon

run nodemon index