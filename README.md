# NBA Shooting Data
This dataset is based on shooting statistics that can be found on [NBA.com](https://www.nba.com/stats/players/shooting/?Season=2020-21&SeasonType=Playoffs&PerMode=Totals). It consists of shots taken by four different players during the 2021 NBA Playoffs.

----------------------------------------------------------------------
#### Data Dictionary

|variable |class     |description                                                  |
|:--------|:---------|:------------------------------------------------------------|
|SHOOTER  |String    |Name of the player taking the shot                           |
|X        |float     |Horizontal distance of the shot taken from the baseline in ft|
|Y        |float     |Vertical distance of the shot taken from the baseline in ft  |
|RANGE    |String    |Radius range of the shot taken from the baseline in ft       |
|DEFENDER |String    |Name of the player defending the shot                        |
|SCORE    |String    |'MADE' if shot is scored, else 'MISSED'                      |

----------------------------------------------------------------------

This analysis was developed using Python. With it, i tried to look at players shooting efficiency overall, when defended by different players and in different zones of the court.

I also flipped the logic and looked at the defensive impact of the players in our dataset.

Shot charts for the players were also created for this project, with the intention of visualizing the court and the areas where players are more or less efficient.
