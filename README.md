# Machine-Learning-MLB-DFS
Comparing previous winning stats of players using Machine Learning to select pitchers and hitters for the current day with the purpose of creating lineups for Fantasy Baseball..

Machine Learning MLB DraftKings/FanDuel Selection

There are a few files not included here for the sake of simplicity and to not begin to become to convoluted.

Purpose:
This python 2.7 program trains models off previous stats from past winners of MLB Fantasy such as Draft Kings and Fanduel.

1. It takes previous readouts from the last week of stats. Takes the winners from those nights of everyone in the top 10 of lineups. Mark them and train models of the previous weeks and make choices based on similar stats of the current day your going to play.

I’ve included the example months.

ML_MLBDFS_SHEET_1
There is a name difference between FanGraphs and the DKS/FD cvs sheets this will
match the proper name with the stats and the player id number.

ML_MLBDFS_SHEET_2
Will grab several stats over a period of days to train model using excel sheets
Batters and Hitters on Different sheets. This will combine all of those records
to use to train the model. Its a classifier so 1 is selected 0 is non-selected.

ML_MLBDFS_SHEET_3
Uses Combined data over the last week to train model and make selections
from current play day. This will spit out the Pitcher and Batters you should select for use in your line up.
