# Setup

### Create DB
psql -U postgres

CREATE DATABASE twitter_clone;

\c twitter_clone;

\dt

### Create tables and seed
modify connection string - postgresql://postgres:password@localhost:5432/database_name

python seed.py

psql -U postgres

\c twitter_clone;

\dt

flask run
