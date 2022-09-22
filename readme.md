# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

# Install process

Firstly verify if Docker is running by using these commands in the terminal;

docker -v
docker-compose -v

Then, run docker-compose up from the project root directory to load both backend and frontend.

If docker is running correctly use the following link to test http://localhost:3000/api/ping

Now it is time to check the frontend and make sure it's connected to the backend.

To do this head over to http://localhost:3001/register and create a new user name.