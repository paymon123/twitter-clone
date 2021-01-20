# Setup

### Create DB
psql -U postgres

CREATE DATABASE warbler;

\c warbler;

\dt

### Create tables and seed
modify connection string - postgresql://postgres:password@localhost:5432/database_name

python seed.py

psql -U postgres

\c warbler;

\dt

flask run
