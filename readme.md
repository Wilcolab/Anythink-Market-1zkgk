# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1st --> clone repository to local host
2nd --> Download Docker and WSL2 (Windows Subsystem for Linux) if you do not have it
3rd --> check that docker is running smoothly by inputting the following commands "docker -v" and "docker-compose -v"
4th --> from the project's local root directory input the following commands "docker-compose up"
5th --> open "http://localhost:3000/api/ping" to make sure everything is running smoothly
6th --> open "http://localhost:3001/register" and create a test user.
