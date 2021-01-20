#Instructions to run
psql -U postgres
CREATE DATABASE warbler;
\c warbler;
modify connection string - postgresql://postgres:password@localhost:5432/database_name
python seed.py
flask run
