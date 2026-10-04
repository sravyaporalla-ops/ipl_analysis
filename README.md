# IPL Data Analysis

## Project Title

IPL Performance Analytics Dashboard

## Objective

The objective of this project is to analyze IPL team and player
performance, match outcomes, batting and bowling performance, venues,
toss decisions, and season-wise trends. The analysis uses Python for
data cleaning, statistical analysis, and visualization, and Power BI for
interactive dashboard development.

## Dataset

The project uses cleaned IPL match-level and ball-by-ball data.

### Dataset Files

-   `IPL_Cleaned.csv` - cleaned ball-by-ball IPL data
-   `IPL_Matches_Cleaned.csv` - cleaned match-level IPL data

Important fields include Match_ID, Season, Match_Date, City, Venue,
Team1, Team2, Toss_Winner, Toss_Decision, Winner, Player_of_Match,
Batting_Team, Bowling_Team, Batsman, Bowler, Runs_Scored, Extra_Runs,
Total_Runs, Wickets, Over, and Ball.

## Tools Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook / Google Colab
-   Microsoft Power BI Desktop
-   Power Query
-   DAX

## Data Cleaning

The data was checked for data types, missing values, and duplicate
records. Duplicate records were removed and inconsistent team names were
standardized. Dates were converted to the appropriate date format,
missing values were handled, and the cleaned datasets were used for
further analysis.

## Data Analysis

The project includes analysis of: - Total matches - Matches by season -
Wins by team - Player of the Match awards - Most-used venues - Toss
decisions - Toss winner versus match result - Winning margins - Top run
scorers - Top wicket takers - Season-wise total runs - Season-wise total
wickets - Average runs per match - Team-wise average runs - Season-wise
team performance - Venue-wise performance - Major IPL performance trends

## Python Visualizations

The Python analysis includes: 1. Matches Played by Season 2. Matches Won
by Team 3. Top 10 Run Scorers 4. Top 10 Wicket Takers 5. Player of the
Match Awards 6. Toss Decision Distribution 7. Matches Won After Winning
Toss 8. Season-wise Total Runs 9. Season-wise Total Wickets 10. Runs
Distribution 11. Team Performance Comparison 12. Venue-wise Match Count
13. Runs vs Wickets 14. Correlation Heatmap

## Power BI Dashboard

The Power BI dashboard is titled **IPL Performance Analytics
Dashboard**.

It includes: - Total Matches - Total Runs - Total Wickets - Total
Teams - Total Players - Average Runs - Matches by Season - Wins by
Team - Top 10 Batsmen - Top 10 Bowlers - Runs by Season - Matches by
Venue - Toss Decision Distribution - Player of the Match - Team
Performance Matrix - Season slicer - Team slicer - Venue slicer

## Key Insights

-   Mumbai Indians recorded the highest number of wins.
-   The 2013 season recorded the highest number of matches, with 76
    matches.
-   AB de Villiers received the highest number of Player of the Match
    awards, with 25.
-   Virat Kohli was the leading run scorer, with approximately 8.0K
    runs.
-   Yuzvendra Chahal was the leading wicket taker, with 205 wickets.
-   Wankhede Stadium was the most frequently used venue, with 118
    matches.
-   Field was the most common toss decision, with 704 matches (64.29%).
-   Toss winners won 50.83% of matches, indicating only a slight
    advantage.
-   2024 recorded the highest season total of 25,971 runs.
-   Gujarat Titans had the highest average runs per innings, at 172.38.
-   Average runs per match increased from 309.3 in the first season to
    365.8 in 2024.

## Project Files

``` text
Sravyaporalla_IPL_Data_Analysis/
│
├── Dataset/
│   ├── IPL_Cleaned.csv
│   └── IPL_Matches_Cleaned.csv
│
├── Python/
│   └── IPL_Data_Analysis.ipynb
│
├── PowerBI/
│   └── IPL DATA ANALYTICS.pbix
│
├── Report/
│   └── IPL_Project_Report.pdf
│
└── README.md
```

## Conclusion

The project provides a consolidated analysis of IPL team performance,
player contributions, toss behavior, venues, and season-wise scoring
patterns. Python was used for data preparation, analysis, and
visualization, while Power BI was used to present the findings through
an interactive dashboard.
