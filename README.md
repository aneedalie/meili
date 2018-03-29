# Meili
Travel planning app, to travel with friends without the headache of planning with them.

## Dependencies
1. Install `npm` and `nodemon` globally on your machine.
2. Install `cockroachdb` from [here](https://www.cockroachlabs.com/docs/stable/install-cockroachdb.html) on your machine.
3. To run tests install [bats](https://github.com/sstephenson/bats) and [jq](https://stedolan.github.io/jq/download/).

## Setup
1. In the home directory, run `npm run setup`.
2. Run `npm run start` to start the frontend and backend servers concurrently.
3. Once you see that two servers are running (there might be a compile time lag for the frontend), connect to `localhost:1024` (the port is set to 80) on your browser to see the application running.

## Footnotes
Current code based off of tutorial found [here](https://github.com/auth0-blog/vuejs2-authentication-tutorial).
