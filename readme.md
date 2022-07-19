# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To get started, `git clone` this repo. Next, install [docker](https://docs.docker.com/get-docker/).

Inside the root directory alongside `frontend` and `backend`, run `docker-compose up` to start the front and back end.

Finally, navigate to `http://localhost:3000/api/ping` and `http://localhost:3001/register` to verify that everthing is working correctly.