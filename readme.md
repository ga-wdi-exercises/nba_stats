# SQL Clauses & Aggregation

### Part 1

Run `gem install sqlite3` to install the sqlite gem. The sqlite gem allows us to run SQL in a Ruby file.

Run the `load_data.rb` Ruby program __ONCE__ (use the command: ```ruby load_data.rb```)to populate the database. It reads in the CSV information from the `data.csv` textfile and populates your database. The data is structured like the following:`name,age,team,games,points`

** `games` is games played during the season and `points` is total points scored over the course of the season.

### Part 3

Enter the sqlite prompt:

```
$ sqlite3 nba.db
```

Figure out the appropriate SQL commands to find out the following, and keep track of them in the file called `sql_commands.txt`

1. All columns for all players from the New York Knicks (NYK)
2. All columns for all players from the Indiana Packers (IND) who are under 26 years old
3. All columns for all players, ordered from least points scored to most points scored
4. Name and Points per game (points/games), for the players with the top 20 points per game
5. The average age for all players
6. The average age for all players on the Oklahoma City Thunder (OKC)
7. The average age for all players who played more than 40 games
8. The team and total points scored from all players on that team (team points), ordered from most team points to least

###Bonus
1. Age and the average points per game for that age, ordered from youngest to oldest
2. Team and the the number of players who score above 12 points per game on that team, ordered from most to least
