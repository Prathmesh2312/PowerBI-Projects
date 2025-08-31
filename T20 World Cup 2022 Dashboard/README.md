# Cricket T20 World Cup 2022 - Best 11 Player Analysis
This project, titled "T20 World Cup 2022 Dashboard", aims to identify the best 11 cricket players from the T20 World Cup 2022 based on a data-driven approach. I have used web scraping to collect player statistics, performed data cleaning and transformation, and then developed a Power BI dashboard to visualize the insights and select the optimal team.

The core objective is to assemble a team capable of:
1) Scoring at least 180 runs on average.
2) Defending a score of 150 runs on average.

## Project Workflow
The project follows a structured workflow to ensure a robust analysis:  
***1) Data Acquisition:*** Player statistics from the T20 World Cup 2022 were scraped from the ESPNcricinfo website. The data was initially collected in JSON format.  
***2) Data Transformation:*** The raw JSON data was converted into a CSV format.  
***3) Data Cleaning & Analysis:*** The CSV data was loaded into a Pandas DataFrame for cleaning and transformation. This step involved handling missing values, standardizing data types, and feature engineering to prepare the data for analysis.  
***4) Dashboard Development:*** A comprehensive dashboard was created in Power BI to present the findings and facilitate the selection of the best 11 players.  

## Player Selection Parameters
The following parameters and criteria were used to select players for each role in the team, as defined in the "Parameter Scoping" document.

**Openers**
* Batting Average: > 30 (Average runs scored in an innings)

* Strike Rate: > 140 (No. of runs scored per 100 balls)

* Innings Batted: > 3 (Total innings batted)

* Boundary %: > 50 (% of runs scored in boundaries)

* Batting Position: < 4 (Order in which the batter played)

**Anchors / Middle Order**
* Batting Average: > 40

* Strike Rate: > 125

* Innings Batted: > 3

* Avg. Balls Faced: > 20 (Average balls faced by the batter in an innings)

* Batting Position: > 2

**Finisher / Lower Order Anchor**
* Batting Average: > 25

* Strike Rate: > 130

* Innings Batted: > 3

* Avg. Balls Faced: > 12

* Batting Position: > 4

* Innings Bowled: > 1

**All-rounders / Lower Order**
* Batting Average: > 15

* Strike Rate: > 140

* Innings Batted: > 2

* Batting Position: > 4

* Innings Bowled: > 2

* Bowling Economy: < 7 (Average runs allowed per over)

* Bowling Strike Rate: < 20 (Average no. of balls required to take a wicket)

**Specialist Fast Bowlers**
* Innings Bowled: > 4

* Bowling Economy: < 7

* Bowling Strike Rate: < 16

* Bowling Style: = "Fast"

* Bowling Average: < 20 (No. of runs allowed per wicket)

* Dot Ball %: > 40 (% of dot balls bowled)