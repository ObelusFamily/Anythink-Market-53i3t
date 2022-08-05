# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Ensure docker is installed on the machine you intend to run this application on.

You can then run the following from the root of the directory.

```bash
docker-compose up
```

This will fetch the required dependencies and then run an instance in your local environment. You can perform a health check at:

```
http://localhost:3000/api/ping
```
