## Data Modeling with Postgres

In this mock project a Postgres database for a small stream music startup is designed. The stream music service wants to analyze the data they've been collecting on songs and user activity on their new music streaming.

Currently, their data resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

To optimize queries on song play analysis **a star schema** base on the information availabe is implemented.  

# Fact Table

| **songplays** |
|--------------|
|  songplay_id |
|  start_time |
|  user_id |
| level |
| song_id |
| artist_id |
| session_id |
| location |
| user_agent |

# Dimension Tables

| **users** |
|-----------|
| user_id |
| first_name |
| last_name |
| gender |
| level |

| **songs** |
|-----------|

| **artists** |
|-------------|


| ***time* |
|----------|
