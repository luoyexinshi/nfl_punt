# Project Overview

For the 2018 season, the NFL revised their kickoff rules in an effort to reduce the risk of injury during those plays. By examining injury reports, player position and velocity data, and game video, they were able to understand the game-play circumstances that may exacerbate the risk of injury to players.

This comprehensive review showed that over the course of all games during the 2015–2017 seasons, the kickoff represented only six percent of plays but 12 percent of concussions. Players had approximately four times the risk of concussion on returned kickoffs compared to running or passing plays.

My project is trying to investigate the what factors cause concussion during a punt play, and what suggestions should be made in order to decrease the risk of concussion on returned kickoffs.

# Data:

The data is provided by The National Football League for NFL seasons 2016 to 2017.

Each dataset can be merged on the game, play or player level using the provided key variables. GameKey provides a unique identifier for a specific game which is unique across NFL seasons. PlayID identifies a unique play within a specified GameKey. GSISID provides a unique identifier for a player across all seasons.

# Files:

• play_information.csv
Play level data that describes the type of play, possession team, score and a brief narrative of each play. Plays are uniquely identified using a its PlayID along with the corresponding GameKey. PlayIDs are not unique.

• player_punt_data.csv
Player level data that specifies the traditional football position for each player. Each player is identified using his GSISID.

• video_review.csv
Injury level data that provides a detailed description of the concussion-producing event. Video Review data are only available in cases in which the injury play can be identified. Each video review case can be identified using a combination of GameKey, PlayID, and GSISID. A brief narrative of the play events is provided.

• nfl_project.ipynb
Data analysis in Python. This was required for project submission in Udacity's Data Scientist Nanodegree program. 

• Medium blog post
You can find a blog post consist of data analysis results [here](https://medium.com/@luoyexinshi/how-to-protect-nfl-players-from-concussion-during-punt-plays-c38945608cb)

# Python Libraries
• numpy 

• pandas 

• matplotlib.pyplot

• display

• seaborn

# Results (Recommendation):

My suggestion is that the ball should be advanced an extra 5 yards on any kickoff or punt when the receiving team doesn’t get a penalty.

This way, the receiving team would have the motivation to be more careful while receiving the ball, hence, hopefully, decrease the concussion rate during the punt.

