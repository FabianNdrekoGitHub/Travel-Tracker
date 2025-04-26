# Travel-Tracker
Travel Tracker is a web app that lets users log visited countries, highlights them on a map, and shows the total count—data is saved in a PostgreSQL database.

Steps
1-Create PostgreSQL DB with 2 tables
  1 - countries 
      CREATE TABLE countries (
        id SERIAL PRIMARY KEY,
        country_code VARCHAR(2) UNIQUE NOT NULL,
        country_name VARCHAR(255) NOT NULL
    );
  2 - visited_country
      CREATE TABLE visited_countries (
        id SERIAL PRIMARY KEY,
        country_code VARCHAR(2) NOT NULL
      );

2-Import data file countries.csv to countries table on DB.
3-Change DB_name and DB_psw

ON TERMINAL
Go to folder path (cd 'folder path')
run (npm i)
run (npm nodemon)
run (nodemon index.js)

 
