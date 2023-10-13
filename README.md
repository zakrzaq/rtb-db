# RTB-DB

## SETUP

To be used as git submodule to [rtb-house](https://github.com/zakrzaq/rtb-house) in `./db` directory.

- setup `.env` file. Example [ENVIRONMENT VARIABLES](#environment-variables)
- run `docker compose up`


## ENVIRONMENT VARIABLES
File: `postgres.dev.env`

```
POSTGRES_DB=rtb_house_db
PGADMIN_DEFAULT_EMAIL=admin@example.com
PGADMIN_DEFAULT_PASSWORD=admin
PGADMIN_LISTEN_PORT=5050
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
```

