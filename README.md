# NBAFantasyStats
These are Juptyer Python files that utilize a NBA API and a Firebase/SQL server for writing and reading player data.
The NBAStatsWriteToGoogle/NBAStatsWriteToSQL are used to pull NBA player data from an API, clean the data, calculate the Fantasy Efficiency Rating for each player and finally write all the player data to a Firebase/SQL server respectively.
The NBAStatsWrite file is used to write the player data to a SQL server.
The NBAStatsRead file is used to read the player data from the SQL server, find the most accurate team size for ranking teams based on player data and finally ranks the teams based on this team size.

# Getting Started

Download the Jupyter files and the required software (See Prerequisites). You will need to update the code to make it work for your own Firebase/SQL server.

# Prerequisites

Required Software:

  - Jupyter
  - Google Firebase Storage or any SQL server software (mySQL, XAMP, etc.)
  
  # Installation
  
  After downloading the Juptyer files and software, update the part of the python code that contains the Firebase/SQL server informtation.
  
  # Author
  
  Gilbert Cherrie
