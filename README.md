# ScoreKeeper
---
### This is a simple Power App project I put together to track scores and stats for my daughter's soccer team. I am still learning GitHub so let me know is you see something I can improve on. This first repository might be a little unconventional.
---
You will find the msapp file attached. This submission might be a little unusual because the app runs off of SharePoint lists. You will need to create a duplicate of these lists and add them to your app. For your convenience I have outlined the lists below.
Games: is a list of all games
GameScoreTracker: is a list of all goals and the scoring players
SeasonsAndTournaments: is a list of all the team's seasons and tournaments
Players: is a list of all Players

Games
---
This list is used to hold games for the team.
Columns:
Title - Title is a required column on all SharePoint lists, every row in this columns simply has the text "game"
Event Type - This is a single line of text column and holds the type of game being played (usually either season or tournament)
Date - This is a date column, it holds the date of the event
Tournament - This is a single line of text column and holds the tournament or season in which the event is being played
HomeTeamScore - This is a number column and contains the score for the team the app is for (in this case this would be my daughter's team)
OpponentScore - This is a number column and contains the score for the opposing team
WLorD - This is a single line of text column and contains the result of the match (W, L, or D)
Notes - This is multi line of text column and contains any notes about the game
Time - This is a single line of text column and contains the time the game is played
Location - This is a single line of text column and contains the location the game is played
Opponent - This is a single line of text column and contains the opponent the game is played against
HomeAway - This is a single line of text column and contains whether the game is played at home or away

GameScoreTracker
---
This list is used to hold all goals and information about the goals.
Columns:
Title - Title is a required column on all SharePoint lists, every row in this columns simply has the text "goal"
GoalsScoredBy - This is a number column and holds the number of the scoring player
GameID - This is a number column and holds the ID (from the Games list) of the game the goal is scored in
FirstAssist - This is a number column and holds the number of the first assist player
SecondAssist - This is a number column and holds the number of the second assist player
TeamScored - This is a single line of text column and holds the information for which team scored
Season - This is a single line of text column and contains the season or tournament in which the game that the goal is scored in is being played

Players
---
This list is used to hold all the information for the players for the team the app is for.
Columns:
Title - This holds the name of the player
PlayerNumber - This is a number column and holds the number of the player
Position - This is a single line of text column and holds the position of the player
Status - This is a single line of text column and holds whether the player is active or inactive

SeasonsAndTournaments
---
This list is used to hold the seasons and tournaments the team is or has participated in.
Columns:
Title - The name of the season or tournament
Default - This is a single line of text column and is used to mark a season or tournament as default

How to use the app
---
I think use of the app is pretty self explanatory. You'll want to add the games being played, the players, and the seasons. Then use the gameday screen to record the scores and the other screen to review results and stats.
