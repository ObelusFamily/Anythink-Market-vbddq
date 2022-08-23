# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _Steps of installation and running the repo on a new machine?_
- Install Docker.
- Verify installation using **_docker -v_** and **_docker-compose -v_** commands.
- If Docker is working correctly, the backend should be running and able to connect to your local database.
- Test this by pointing your browser to **_http://localhost:3000/api/ping_**.
- If the link is working, then the backend is up and running.
- Next check the frontend and make sure it’s connected to the backend.
- If everything is working properly, you’ll be able to create a new user on **_http://localhost:3001/register_**.
