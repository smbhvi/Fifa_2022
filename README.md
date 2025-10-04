# Fifa_2022
Project Overview:
This project performs Exploratory Data Analysis (EDA) on a football dataset containing match-level statistics (64 matches × 88 features).
The goal is to extract key insights into match outcomes, offensive and defensive performance, passing build-up play, and possession strategies.
To make the analysis more interactive and business-friendly, I also built a Power BI Dashboard showcasing team performance, match trends, and winning factors.

Dataset
Rows: 64 (matches)
Columns: 88 (team performance metrics)
Features Include:
Goals scored & conceded
Possession % (team1, team2, contested)
Attempts (total, on/off target, inside/outside penalty area)
Assists, passes, crosses, switches of play
Defensive actions (fouls, cards, pressures, goal preventions)
Attacking zones (left, central, right)
Match date & time


Match Outcomes
Bar chart of average goals scored vs conceded.
Pie chart of Win/Draw/Loss distribution.

⚔️ Offensive Analysis
Scatter plots: Attempts, On-target attempts, Assists, Passes completed vs Goals.
Heatmap: Inside vs Outside penalty attempts correlation with goals.

🛡️ Defensive Analysis
Boxplots: Fouls, Yellow/Red cards per team.
Scatter: Defensive pressures vs Goals conceded.


Tech Stack
Python: Data cleaning, preprocessing, correlation & EDA.
Libraries: Pandas, Matplotlib, Seaborn.
Power BI: Interactive visualizations & storytelling.
