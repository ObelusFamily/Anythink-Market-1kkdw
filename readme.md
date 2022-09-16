# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- First thing’s first - [install Docker](https://docs.docker.com/get-docker/)
- Check if docker is running `docker -v` and `docker-compose -v`.
- On the root folder start by running `docker-compose up`.
- backend-servire will start on port `3000` [localhost:3000](http://localhost:3000/api/ping)
- front-end will start on port `3001` [localhost:3001](http://localhost:3001/register)
- Done
