# The prediction of ranking range of a soccer team in Big 5 league
Zimu Su

## Question/Need

The ranking range cannot be overemphasized for a soccer team in Big 5 league (the Premier League in England, La Liga in Spain, the Bundesliga in Germany, Serie A in Italy and Ligue 1 in France) because it is not only relevant to reputation but influence the team’s revenue as well. Those teams at the bottom of the league will  be relegated to the league at inferior level and lose a huge amount of revenue or even cannot afford to pay for the expensive of team players. Those top ranked teams can acquire the qualification to attend the league held by Union of European Football Associations (UEFA League) and receive additional revenue through worldwide broadcasting. By analyzing and predicting the rank range of a soccer team based on the performance statistics in the previous seasons, the team manager can put forward strategy to strengthen the team (e.g. recruiting the player to supplement the weakness at certain position) and achieve the expected goal in the coming season.

## Data Description

The data will be scraped from fbref.com through beautiful soup. The model aims at predicting whether the teams in Big 5 League will acquire qualification of UEFA (top 6 or 7 depending on the league), relegate to the inferior league(drop at the lowest 3 ranking) or stay in the middle range at the end of the season, based on the statistics of team-level performance which is collected in one season. The features will be divided into the aspects of team shots (shots on target percentage, shots per game), defensive actions (block, interceptions, tackles, dribble tackles percentage), and goal keeping.

## Data

The datasets include 590 team statistics from Big 5 European league and Major League Soccer (MLS) in United States within 2017 - 2021 season. The goal scoring of one team per game in one season is employed as target. The features can be categorized into the aspects of shots (shots on target percentage, shots per game), possessions (possession rate, average passes percentage, dribbles successful rate) and defensive actions (block, interceptions, tackles, dribble tackles percentage). Pair plot and variance inflation factor are inspected to exclude the collinearity.

## Tools

*Web scraping*
Build a pipeline to collect the datasets from fbref.com using python module beautiful soup.

*Aggregation & feature engineering*
Python pandas

*Models* 
Scikit learn

*Visualization*
Seaborn, Tableau


## MVP goal

A preliminary regression analysis for the aforementioned prediction.



