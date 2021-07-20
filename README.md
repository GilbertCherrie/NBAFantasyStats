# NBAFantasyStats
These are Juptyer python files that utilize a NBA API and a SQL/Google Firebase server for writing and reading player data.
The write files will write NBA fantasy point stats to an SQL server.
The NBAStatsWrite file can be used for any season in NBA history but is slower to run than the NBAStatsWriteActivePlayers which is faster since it only uses active players, not every single player in NBA history, however it is only useful for the current season since it will be missing some player info for retired or injured players.
The NBAStatsRead file is used to read the data from the SQL server, find the most accurate team size for ranking teams based on player data and finally ranks the teams based on this team size.

# Getting Started

Download the Jupyter files and the required software (See Prerequisites). You may need to update the code to make it work for your own SQL server.

# Prerequisites

Required Software:

  - Jupyter
  - Any SQL server software (mySQL, XAMP, etc.)
  
  # Installation
  
  After downloading the Juptyer files and software, update the part of the python code that contains the SQL server informtation. Update
  the server username, password, name and table name.
  
  # Author
  
  Gilbert Cherrie
