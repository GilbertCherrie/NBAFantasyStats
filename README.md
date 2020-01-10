# NBAFantasyStats
These are Juptyer python files that utilize the nba api and an SQL server for writing and reading player data.
The write files will write NBA fantasy point stats to an SQL server.
The NBAStatsWrite file can be used for any season in NBA history but is slower to run than the NBAStatsWriteActivePlayers which is faster since it only uses active players, not every single player in NBA history, however it is only useful for the current season since it will be missing some player info for retired or injured players.
The NBAStatsRead file is used to read the data from the SQL server, find the most accurate team size for ranking teams based on player data and finally ranks the teams based on this team size.
