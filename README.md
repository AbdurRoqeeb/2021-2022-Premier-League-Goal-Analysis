# 2021-2022-Premier-League-Goal-Analysis
----
## Problem Statement
#### The goal of this project is to know
1. Total number of goals scored in the season.
2. Distribution of goals scored at Home by each team throughout the season.
3. Distribution of goals conceded at Home by each team throughout the season.
4. Number of Hometeam and AwayTeam goals scored in each month throughout the season.
5. Top 5 teams with the most goals conceded.
6. Top 5 teams with the most goals scored.
7. Top 5 months with the most goals scored in them.
----
## Data Sourcing
Data used was gotten from https://www.kaggle.com/datasets/azminetoushikwasi/epl-21-22-matches-players

----
## Data Cleaning
I changed the data type of the date column to date, thn extracted the month name from the date column.
I splitted the result column to create two new columns: HomeTeam Goals and AwayTeam Goals. I used these two columns to create a calculated column for the total goals scored in each match.
Analysis and visualization was done with Microsoft Power BI.

----
## Findings
1. The season had a total goals of 1071
2. Manchester City scored the most goal at home and overall (58 at home, 99 overall).
3. Watford conceded the most goal at home (46).
4. Norwich City conceded the most goal overall (84).
5. The month in which the most goal was scored is December 2021 (156).
