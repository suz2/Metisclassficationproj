# The prediction of ranking range of a soccer team in Big 5 league
Zimu Su

## Question/Need

The ranking range cannot be overemphasized for a soccer team in Big 5 league because it not only relevant to reputation of a team but influence the team’s revenue as well. Those teams which relegate to interior level league will lose a huge amount of revenue and even cannot afford to pay for the expensive of team players, while those top 6 or 7 teams can acquire the qualification to attend UEFA League and got additional revenue through broadcasting. By analyzing and predicting the rank range of a soccer team based on the performance statistics in one season, the team manager can put forward strategy to strengthen the team (e.g. recruiting the player to supplement the weakness at certain position) and achieve the expected goal in the next season.

## Data Description

The data will be scraped from fbref.com through beautiful soup. The model will predict whether soccer team in Big 5 League will acquire qualification of UEFA (top 6 or 7 depending on the league), relegate (the lowest 3 ranking) or in the middle range, based on the performance statistics in one season such as goals, passing success percentage, tackle rate, dribbles, pressures, etc.

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



