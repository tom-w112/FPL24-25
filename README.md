# Fantasy Premier League, Season Review 2024-25

## Overview
Fantasy Premier League (FPL) challenges players to build a virtual team that scores points based on real-world football performance. This report uses 2024-25 season data from Vaastav's GitHub repo to present an Exploratory Data Analysis (EDA), focusing on player price, performance, and key positional insights for making data-driven decisions.

## Motivation
I  chose this project to demonstrate my end-to-end **data management capabilities**, spanning the entire lifecycle from **data discovery, sourcing, and loading** to **filtering, refining, and analysis**. 
My keen support for Wolverhampton Wanderers made Fantasy Premier League a natural and engaging topic, and builds on my growing experience in the field of sports data.

## Data Source
The data utilised for the report came from Vaastav's Fantasy Premier League GitHub repository, which can be found at: https://github.com/vaastav/Fantasy-Premier-League.
Player data was used from data/2024-25/players_raw.csv and gameweek data from data/2024-25/gws.

## Methodology
The report is structured around several notebooks:
- 00_Data_Loading.ipynb: Handles the initial **sourcing and loading of the raw data**.
- 01_Data_Processing.ipynb: **Data Cleaning, Transformation and Aggregation**.
- 02_EDA.ipynb: Conducts initial **exploratory data analysis** for initial insights and relationships.
- Thoughts_and_Findings.ipynb: Serves as the current findings report, **summarising plots, insights and conclusions**.

## Findings
The initial analysis uncovered several insights, key of which included:
- The strong relationship between players' performance in the **Bonus Points System (BPS)**, and their overall **total points**.
- Significant differences in **player performance across positions** and their respective **returns on investment (points per million)**.
- The relevance of the **ICT Index** when assessing between the value of players at different price points.

## Next

Future additions to the report will include:

- Fixture Difficulty analysis: how points scored changes depending on the opposition.
- Team analysis: how the team of a player impacts their performance & scores.
- ML for team assembly & player picking.

Additionally, in preparation of the 2025-26 Season, several blocks in 00_Data_Loading.ipynb have been set up to sync directly from the Premier League's API, to allow for further reporting during the upcoming season.
