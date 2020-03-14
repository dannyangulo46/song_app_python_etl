
## Project description

Create a database that allows data analysts and business users to create queries and find insights into what are the most popular songs.

## Data sources  
1) Metadata about the songs - json files
2) User activity in the website - json files

## Database design  
The design will consist in creating a fact table for the songs played and 4 dimension tables: time, users, songs, artists.  It will be a star schema which will allow to create efficient queries.

## Files included in the repository
1) data folder with data files in json format
2) create_tables.py
3) sql_queries.py
4) etl.py

## How to run scripts
1) Run create_tables.py to create tables
2) Run etl.py to transform data files and load them into fact table and dimension tables




