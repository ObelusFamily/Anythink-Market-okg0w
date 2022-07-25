# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

We use Docker and Docker Compose to develop Anything Market.  What does this mean to you.  Well you need to pull down the impages in order to run the application.  To do this run `docker compose up`  This assumes you have docker installed on your machine.
After docker compose runs lots of stuff on the screen you can test your setup by openning a browser and going to `http://localhost:3001/`  That should bring up the home page for the product.
To stop the product you can press `Ctrl-c` to shutdown Docker.
