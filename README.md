# IPL-ANALYSIS-DASHBOARD-POWER-BI
IPL Analysis Dashboard- POWER BI 

https://app.powerbi.com/links/Y1qSJZp-mF?ctid=30ec8a15-7492-495e-9342-c7e27815e204&pbi_source=linkShare

This project involves building an interactive IPL (Indian Premier League) Analysis Dashboard using Power BI. The dashboard provides insights into IPL matches, player performance, and key metrics such as runs, wickets, and team stats. It includes data from IPL seasons 2008-2024, enabling users to visualize and explore various aspects of IPL history.

Table of Contents

1. Project Overview


2. Technologies Used


3. Data Source


4. Project Steps

Step 1: Data Collection and Cleaning

Step 2: Data Import and Integration

Step 3: Building Key Measures

Step 4: Designing Visuals

Step 5: KPIs and Slicers

Step 6: Adding Interactivity

Step 7: Final Touches



5. Features


6. How to Use


7. Conclusion


8. Future Work



Project Overview

The IPL Analysis Dashboard aims to provide comprehensive insights into IPL matches, players, and teams. By analyzing key performance indicators like runs, wickets, economy rate, batting averages, and team wins, this dashboard helps viewers to track and compare performance across various seasons and matches.

Technologies Used

Power BI for creating the interactive dashboard.

Excel for data manipulation and initial cleaning.

CSV files for storing IPL dataset (ball-by-ball and match data).

DAX (Data Analysis Expressions) for creating calculations and measures.


Data Source

The dataset consists of two primary tables:

Matches Table: Contains details about the matches such as team names, venue, result, match date, season, etc.

Delivery Table: Contains ball-by-ball data, such as runs, wickets, extra runs, batting team, bowling team, player performance, etc.


Project Steps

Step 1: Data Collection and Cleaning

Collected IPL data for seasons 2008 to 2024, including match results, player statistics, and team performance.

Cleaned the data by removing duplicates and correcting errors in the match dates.

Ensured consistency between tables by aligning column names and resolving any discrepancies in data.


Step 2: Data Import and Integration

Imported the cleaned CSV files into Power BI.

Combined both the Matches and Delivery tables using relationships to connect the data for accurate analysis.

Ensured that season, match ID, and team names were consistent across both tables.


Step 3: Building Key Measures

Created DAX measures to calculate essential statistics, including:

Batting Performance: Total runs, highest score, average runs, and boundaries hit.

Bowling Performance: Wickets taken, economy rate, bowling average, and strike rate.

Team Performance: Total wins, matches played, and win percentage.

Player Awards: Orange Cap (for highest run-scorer), Purple Cap (for highest wicket-taker).



Step 4: Designing Visuals

Designed the dashboard layout with multiple visuals, including bar charts, line graphs, pie charts, and tables.

Created interactive filters like slicers for selecting:

IPL seasons.

Specific teams.

Match result (won/lost).


Ensured that the design was user-friendly, visually appealing, and easy to navigate.


Step 5: KPIs and Slicers

Added Key Performance Indicators (KPIs) such as:

Highest Runs Scorer for each season.

Most Wickets taken in a season.

Most Wins for each team.


Implemented slicers to allow users to select specific seasons or teams to dynamically update the dashboard with relevant stats.


Step 6: Adding Interactivity

Integrated interactive elements like:

Hover effects to view detailed player or team stats.

Dynamic chart updates when users select specific years or teams.


Enabled drill-downs for deeper insights into match-level data and performance metrics.


Step 7: Final Touches

Reviewed and polished the dashboard for clarity and accuracy.

Ensured that the dashboard performance was optimal by simplifying queries and reducing unnecessary calculations.

Added a legend and titles to all visuals for better understanding.


Features

Interactive Dashboard: Users can explore various stats such as team performance, player achievements, and match results.

Slicers for Dynamic Filtering: Filter data by IPL seasons, teams, and match results.

Key Metrics: Visualize batting and bowling stats, including runs, wickets, averages, and boundaries.

Season-wise and Player-wise Comparison: Compare players' performance across different seasons and teams.


How to Use

1. Clone or Download the Repository: Clone the repository to your local machine or download the dataset and Power BI file.


2. Open Power BI: Open the provided Power BI (.pbix) file in Power BI Desktop.


3. Interact with the Dashboard: Use the slicers to filter data based on season, team, and player. Hover over visuals for detailed insights.


4. Update Data: If you have new IPL data, update the CSV files and refresh the dashboard to display the latest stats.



Conclusion

This project provides an in-depth analysis of IPL matches and players, offering a visually engaging and insightful dashboard. The project demonstrates my ability to collect, clean, and visualize data using Power BI, along with the use of advanced DAX measures to create meaningful insights.

Future Work

Real-Time Data Integration: Integrate live IPL data feeds to update the dashboard with real-time match results.

Advanced Analytics: Add predictive analytics to forecast team and player performance.

Mobile Optimization: Optimize the dashboard layout for mobile viewing.
