# SEO-Tech-Developer-Football-Fixtures-Project

This project retrieves football match fixtures from the Sportmonks API, stores them in an SQLite database, and displays the stored data.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmadbasyouni10/SEO-Tech-Developer-Project
   cd <repository_name>
    ```

2. Install Dependencies:
  ```bash
   pip install requests pandas sqlalchemy python-dotenv
  ```

3. Create a .env file:
```bash
API_TOKEN=your_api_token_here
 ```

## How To Run
```bash
python your_script_name.py
 ```

## Overview
* Retrieves football match fixtures from the Sportmonks API using requests.
* Parses the JSON data into a Pandas DataFrame (matches_df).
* Creates an SQLite database named soccergames.db using SQLAlchemy (engine).
* Stores the match data into an SQLite table named matches.
* Fetches and prints all rows from the matches table using SQL queries (SELECT * FROM matches;).

