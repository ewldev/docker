# Docker for multi-face detection backend

PostgreSQL database

1. Clone this repo
2. Run `npm install`
3. You must add your own API key in the `controllers/image.js` file to connect to Clarifai API
4. Add your own database credentials to `server.js` line 12
5. Run docker compose up --build

You can grab Clarifai API key [here](https://www.clarifai.com/)

** Make sure you use postgreSQL instead of mySQL for this code base.
