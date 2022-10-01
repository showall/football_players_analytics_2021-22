# Data Science NanoDegree Capstone 1

## Introduction

This data set contains the match logs of active football/soccer players in the top 5 European Soccer Leagues in 2021/22 season. The dataset contains the performance stats of individual players in matches played across the 2021/22 season. The data dictionary of the dataset is in the next section.

The project aims to provide a sytematic answer to identify best peforming players across the five leagues. Given that all players perform different functions across the field, it is better to divide into segments according to the roles. 

Not all roles priorities the same attributes or qualities, which the why the project will involve looking at each position and pick up some qualities that we think defines that position on the field. For example, a Centre-Forward should be rated based on their goal scoring records and how effective is their conversion rate i.e how many goals per attempt on goal. For the case of midfielders, it is very tricky to actually pick the "best" midfielders because each midfielder has different functional roles. In this project, we will demonstrate by focusing only on the attacking attributes of midfielders.

The data set also consists of some null values which needs to be taken care of. Some additional features are added to create qualities that are found relevant and important (to a position)

## Directory

DSND - Capstone 1
|- README.md
|- Udacity -NDDS - Capstone1
|- fbref_stats_2021_22_Five_European_Leagues.csv


## Tools and Softwares

The project was implemented in Jupyter Notebooks using Python with libraries like 
Pandas

To access notebook using terminal :

```
jupyter notebook Starbucks_Capstone_notebook.ipynb

```

### Business Problem Statements

Mainly, we want to answer from the dataset who are :- 

a) The Best Performing Best Goalkeepers across top 5 European Soccer Leagues in footballing 2021/22 season ?

b) The Best Performing Best Centrebacks across top 5 European Soccer Leagues in footballing 2021/22 season ?

c) The Best Performing Best Midfielders(attacking attributes) across top 5 European Soccer Leagues in footballing 2021/22 season ?

d) The Best Performing Best Centre-Forward across top 5 European Soccer Leagues in footballing 2021/22 season ?

### Data

The main data file is  fbref_stats_2021_22_Five_European_Leagues.csv


### Data Cleaning and Data Engineering

Missing data operations and features engineering to augment the data set. 
Data sets are divided into segments to answer the questions posed in the problem statements. 
Further, a "scoring" column is added to be used for ranking for each segment. 


### Analysis and Justification

The results are shown as tabular and graphical form in the .ipynb file. 


### 5. Report and Github

A presentation report can also be found in  https://medium.com/@gerardsho/who-stood-out-in-the-2021-22-football-season-dd671eb293dc
The github repository has been stored in https://github.com/showall/football_players_analytics_2021-22.git