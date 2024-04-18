# Docker postgre config

## Setup

Copy the `.env.example` file to `.env` and set the environment variables. \
You can change the `POSTGRES_USER`, `POSTGRES_PASSWORD` and `POSTGRES_DB` variables to your desired values.

```bash
cp .env.example .env
```

### Run

```bash
docker-compose up
```

### Stop

```bash
docker-compose down
```

## PGAdmin

Access the pgAdmin interface at `http://localhost:8080` and login with the credentials set in the `.env` file. \
You can change the `PGADMIN_DEFAULT_EMAIL`, `PGADMIN_DEFAULT_PASSWORD` ang `PGADMIN_LISTEN_PORT` variables in the `.env` file.