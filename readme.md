# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
Follow Below Steps for system setup

1. install-dockers "for windows or linux - Based on your work system OS.)

2. run below commands in your terminal.

   > docker -v
   > docker-compose -v

3. Navigate to project root directory and run below docker command.
   docker-compose up

   If Docker is working correctly, the backend should be running and able to connect to your local database.
   test this by pointing your browser to http://localhost:3000/api/ping

4. Now navigate to http://localhost:3001/register (to create new user account).

5. Create a new use account
