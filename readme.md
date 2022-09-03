# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

STEP1: Install Docker
Refer to https://docs.docker.com/get-docker/ and follow the instruction for installing
the latest version of Docker corresponding to the OS of your device.

STEP2: Verify that docker is ready by running `docker -v` and `docker-compose -v` in your terminal.

STEP3: Confirm if Docker is working correctly
Pointing your browser to http://localhost:3000/api/ping

STEP4: Check the frontend and backend with http://localhost:3001/register
You should be able to create a new user over here.