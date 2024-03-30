
NBA Player Performance Analysis
Overview
The use of big data has revolutionized the basketball industry, particularly in analyzing player performance. Traditionally, basic box scores were used for tracking player and team performance. However, modern basketball analysis heavily relies on advanced player performance metrics. In this project, we utilized the Historical NBA Raptor dataset provided by FiveThirtyEight, which spans from 1977 to 2022. This dataset contains individual player stats along with advanced performance metrics such as WAR, RAPTOR, PREDATOR, and Pace Impact.

Dataset Description
Content: The dataset contains individual player statistics, including player name, player ID, year of season, season type, NBA team, minutes played, and number of possessions. Additionally, it includes advanced player performance metrics such as WAR, RAPTOR, PREDATOR, and Pace Impact.
Supplementary Variables: To aid in exploratory and explanatory visualizations, we added variables such as season_count, career_ranking, made_playoffs, warrank, and top_player.
Data Filtering: Rows with minutes played (mp) less than 200 were filtered out to ensure the reliability of metrics. This filtering eliminated outliers and provided more accurate metric values for analysis.
Visualizations
Correlation Matrix for Numerical Variables: This visualization explores the correlation between various numerical variables.
Box Plots (Minutes Played): Compares the distribution of raptor_total for different values of mp (minutes played).
Player Analysis of War_total Vs. Minutes Played Statistics: Investigates the relationship between war_total and minutes played for players during the 2019 – 2022 seasons.
Time Series: Average RAPTOR Offense & Defense: Presents average RAPTOR offense and defense on a single graph, filtered for mp>=200.
Mosaic Plot for WAR Performance [2021]: Analyzes the relationship between various statistical categories and teams' ability to make playoffs during the 2021 season.
Analysis of Playoff vs. Non-Playoff Teams from 2019 to 2022: Evaluates the effectiveness of war_total and raptor_total in predicting playoff qualification for NBA teams.
Analysis of Top Players by Team: Illustrates the number of "Top Players" by season and across teams, helping to understand team performance in relation to player statistics.
NBA Player Career Performance Analysis: Examines the career progression of NBA players based on their regular season performance, comparing the top 30 historic players with the entire NBA population.
Conclusion
This project showcases the significance of advanced player performance metrics in analyzing player and team trends over time in the basketball industry. Through exploratory visualizations and data analysis, we've gained insights into player performance, team dynamics, and career progression, which can be invaluable for teams, coaches, and analysts.

For further details and visualizations, please refer to the respective sections above.

(Note: This README provides an overview of the project, including dataset description, visualizations, and conclusions. For detailed analysis and visualizations, refer to the project files.)
