# Illuvium land analytics data loader
This app reads ImmutableX API and fetches all the relevant data for further analytics usage

## Env
The `dotenvy` crate is used to load environment variables needed for DB connection from `.env` file
Also, feature flags are stored there as well.

## Setting up the environment
Execute [start-local-environment.sh](environment/start-local-environment.sh) to spin up Postgres.
It will execute required migrations