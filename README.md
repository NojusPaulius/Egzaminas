# Egzaminas

To start using the app you must launch both backend and frontend at the same time.

1. use "git clone "url of this git repository" .
2. "cd backend", "npm i" and then "npm start"
3. in a new terminal, backend must run in background. "cd frontend", "npm i" and then "npm start"

After this enjoy the websire, DO NOT forget to add your config.env file in backend.
the values it MUST have are:
1. "DATABASE" this includes the link to your mongo database
2. "DATBASE_Password" this is your database password, which you need to access the database
3. "PORT" this shows which port it will connect to
4. "JWT_EXPIRES_IN" ex. 3d, this shows how long a users login session will last
