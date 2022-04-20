# Prediction of hit-and-run traffic accidents in Nashville, Tennessee
Zimu Su

## Abstract

A hit-and-run accident occurs when someone causes an accident and leaves the scene without providing information about themselves. It can cause severe injuries to the victims and their properties without any penalty or blame to the drivers who cause the accidents. This project aims at identifying the significant factors that makes the driver to flee away from the accidents from the perspective of damage properties, type of collision and harm, weather and illumination condition, demographics. Conclusions can be beneficial for Nashville Metro police who can take measures to reduce rate of hit-and-run accidents.

## Design

The observation in the dataset stands for the information of one specific accident. The accident is either hit-and-run or not. The probability of hit-and-run accident is predicted using classification algorithm based on features of an accident.## Data

## Data

The dataset is originally collected from [Data.Nashville.gov](https://data.nashville.gov/Police/Traffic-Accidents/6v6w-hpcw). Each row stands for the information of a reported traffic accident. The model will predict whether an accident would be hit-and-run based on the features of accidents: number of injuries, property damage, collision type, weather condition, daylight condition, zip code.

## Algorithms

* Convert the categorical variables (e.g. weather type, collision code, etc) to dummy variables.
* Perform EDA to inspect the hit-and-run accident numbers for each feature and do feature engineering.
* Use logistic regression with regularization and random forest decision tree method to obtain the optimal f1 score and ROC AUC score.
* Interpret the coefficients and corresponding odds for each feature.
* Try XGboost for the regression.

## Tools

Python Pandas, Scikit learn, Matplotlib, Seaborn, Tableau, XGboost

## Communication

The project is under supervision of Dimitri Theoharatos and delivered on 4/20/2022
