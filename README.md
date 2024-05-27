## IPL Insights: Cricket Dashboard using Cricbuzz API in Power BI

## Overview
**IPL Insights** is an interactive dashboard built in Power BI that provides **real-time and historical analytics** of IPL matches using data sourced from the **Cricbuzz API** via RapidAPI. This comprehensive dashboard offers stakeholders **valuable insights** into player performances, team statistics, and match dynamics, enabling **data-driven decision-making**.

### Table of Contents
- [Installation](#installation)
- [Data Source](#data-source)
- [Data Preparation](#data-preparation)
- [Dashboard Features](#dashboard-features)
- [DAX Measures](#dax-measures)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Data Source
IPL Insights leverages the Cricbuzz API provided by RapidAPI to access detailed data on IPL matches, player performances, and team statistics.

## Data Preparation
API Integration:

## Utilized the Cricbuzz API to fetch real-time and historical IPL data.
Implemented API endpoints in Power BI using blank queries.
Data Extraction:

## Fetched data stored in Power BI tables, organized by batsman info, bowler info, team info, live matches, and live data.
Additional data preprocessing steps performed to ensure data accuracy and consistency.
Dashboard Features
IPL Insights offers stakeholders a wide range of features, including:

## Live Match Analysis:
Real-time updates on ongoing IPL matches, including live scores, player performances, and match events.
Dynamic visuals illustrating match progress, key milestones, and match dynamics.
Player Performance Metrics:
Detailed statistics on individual player performances, including runs scored, wickets taken, strike rates, and economy rates.
Comparison tools to evaluate player performances across matches and seasons.
Team Analysis:
Comprehensive insights into team statistics, including win-loss records, run rates, average scores, and bowling figures.
Visualization tools to compare team performances, identify trends, and analyze strategies.
Match Insights:
Historical analysis of past IPL matches, including match outcomes, top performers, and critical moments.
Trend analysis to identify patterns, rivalries, and performance trends across seasons.
DAX Measures
IPL Insights utilizes advanced DAX measures to calculate various performance metrics, including:

## Batting Metrics:
Dot Balls: Number of deliveries faced by the batsman that resulted in no runs.
Strike Rate: Percentage of runs scored per 100 balls faced.
Sixes: Total number of sixes hit by the batsman.
Fours: Total number of boundaries (4 runs) hit by the batsman.
Player Current Score: Total runs scored by the batsman in the current match.
Team Total: Total runs scored by the team.
Team Run Rate: Average runs scored by the team per over.
Team Total Sixes: Total number of sixes hit by the team.
Team Total Fours: Total number of boundaries (4 runs) hit by the team.
Sixes Contribution: Percentage of total team runs contributed by sixes.
Four Contribution: Percentage of total team runs contributed by fours.
Bowling Metrics:
Wickets Taken: Total number of wickets taken by the bowler.
Runs Given: Total runs conceded by the bowler.
Economy Rate: Average number of runs conceded per over.
Wides Given: Total number of wide deliveries bowled by the bowler.
These DAX measures provide quantitative insights into player and team performances, allowing stakeholders to analyze batting and bowling statistics effectively.

## Usage
To utilize IPL Insights:

Open the Power BI file: Launch Power BI Desktop and open the IPL_Insights.pbix file.
Refresh Data: Click on the Refresh button to fetch the latest IPL data from the Cricbuzz API.
Navigate: Explore different tabs and visualizations to gain insights into live matches, player performances, and team statistics.
Interact: Use slicers, filters, and interactive visuals to customize data views and explore specific metrics of interest.
