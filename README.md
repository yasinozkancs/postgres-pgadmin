# Postgres + PgAdmin

Docker Compose file for running Postgres and PgAdmin.

## Usage

1. Clone this repository.
2. Run `docker-compose up -d` to start Postgres and PgAdmin.
3. Open `http://localhost:5050` in your browser and login with `email@example.com` and `password` to access PgAdmin.
4. Create a new server in PgAdmin with the following settings:
   - Hostname: `postgres`
   - Port: `5432`
   - Username: `user`
   - Password: `password`
   - Database: `postgres`
