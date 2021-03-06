# CityMain

CityMain is a spaced repetition application for learning national capitals. It was built within 5 days by [Joe Pena](https://github.com/Joe-Pena) and [Timothy Chang](https://github.com/continuouslylearning).

## Use this app

### Heroku
CityMain is deployed on Heroku [here](https://javthon-client.herokuapp.com/dashboard).
### Demo account
You can register a new user account or use this demo account.

- Username: demoaccount (All lowercase)
- Password: password123

## Install locally
CityMain can be installed and run locally. You must install both the server and client repos.
### Server
Clone the server from [this github repository](https://github.com/thinkful-ei24/timothy-joe-javthon-server.git). Run `npm install` from within the project folder to install the project dependencies. Then set values for the `DATABASE_URL` and `JWT_SECRET` environment variables inside your terminal. Run `npm start` to start the server.

### Client
Clone the client from this repo. Run `npm install` from within the client project folder to install the dependencies and run `npm start` to serve the client to your browser. Finally, view `http://localhost:3000/` within your browser to begin using CityMain!


## Tech stack
### Front end
- React
- Redux

### Back end
- Node.js
- Express
- MongoDB



