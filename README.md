# Instructions to run

### Create DB
psql -U postgres
CREATE DATABASE warbler;
\c warbler;
\dt

### Create Tables and Seed
modify connection string - postgresql://postgres:password@localhost:5432/database_name
python seed.py
psql -U postgres
CREATE DATABASE warbler;
\c warbler;
\dt

flask run
