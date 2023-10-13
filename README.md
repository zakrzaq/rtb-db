# RTB-DB

## Requirements

docker compose - v2

## Setup

To be used as git submodule to [rtb-house](https://github.com/zakrzaq/rtb-house) in `./db` directory.

1. .env

- setup `postgres.dev.env` file. [example](#environment-variables)

2. docker setup:

- to run the Docker image execute 'docker compose up'

### ENVIRONMENT VARIABLES

File: `postgres.dev.env`

```
POSTGRES_DB=rtb_house_db
PGADMIN_DEFAULT_EMAIL=admin@example.com
PGADMIN_DEFAULT_PASSWORD=admin
PGADMIN_LISTEN_PORT=5050
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
```
