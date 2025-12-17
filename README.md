# ICC-Cricket-World-Cup-2023-Analysis-Report
This project involves an in-depth data analysis of the ICC Cricket World Cup 2023 using Python to extract meaningful insights about player performance, match dynamics, venue behavior, and pressure situations. The analysis was performed on real match datasets, covering batting, bowling, match results, and venue information.

________________________________________
Project Overview
This project focuses on analyzing the ICC Cricket World Cup 2023 using Python to uncover meaningful insights related to player performance, match outcomes, venue behavior, toss impact, and pressure situations.
The goal of this analysis is to demonstrate end-to-end data analysis skills, including data cleaning, exploratory data analysis (EDA), feature engineering, and visualization using real-world sports data.
________________________________________
Objectives
•	Understand player performance under different match conditions
•	Identify top batsmen and bowlers based on multiple performance metrics
•	Analyze pressure performances (successful chases, death overs)
•	Study venue impact on match outcomes
•	Compare batting first vs chasing advantages
•	Use data visualization to communicate insights clearly
________________________________________
Dataset Description
The project uses multiple CSV datasets:
•	Batting data – runs, balls, boundaries, dismissals
•	Bowling data – wickets, economy, overs, maidens
•	Match results – winners, innings outcomes
•	Match & venue data – venues, toss, match details
•	Player information
All datasets were validated and cleaned before analysis.
________________________________________
Tools & Libraries Used
•	Python
•	Pandas – data manipulation
•	NumPy – numerical operations
•	Matplotlib – data visualization
•	Seaborn – statistical visualizations
•	Jupyter Notebook
________________________________________
Data Cleaning & Preparation
Key steps performed:
•	Standardized column names (lowercase, snake_case)
•	Removed extra spaces and fixed inconsistent team/player names
•	Handled missing values logically
•	Created derived columns such as:
o	Batting average
o	Strike rate
o	Bowling average
o	Economy rate
o	Pressure performance indicators
•	Ensured consistent match and player mappings across datasets
________________________________________
Exploratory Data Analysis (EDA)
The analysis includes:
•	Distribution of runs and wickets
•	Top run scorers and wicket takers
•	Strike rate and economy comparisons
•	Centuries and half-centuries analysis
•	Venue-wise scoring trends
•	Toss and innings impact
Various bar charts, stacked bars, and horizontal plots were used for clarity.
________________________________________
Key Analysis Sections
Player Performance Under Pressure
•	Identified players who scored 50+ runs in successful chases
•	Highlighted clutch performers in high-pressure situations
Venue & Toss Impact
•	Compared win percentages for:
o	Batting first
o	Chasing
•	Analyzed venues favoring high first-innings scores
•	Found venues with strong chasing advantages
Top 10 Batsmen Analysis
Metrics used:
•	Total runs
•	Average
•	Strike rate
•	Centuries & half-centuries
•	Boundary counts
Top 10 Bowlers Analysis
Metrics used:
•	Total wickets
•	Bowling average
•	Economy rate
•	Strike rate
•	Best bowling figures
Visualization
•	Bar charts for top performers
•	Stacked bars for 50+ scores
•	Venue-wise comparisons
•	Clean, readable plots suitable for presentations
________________________________________
Key Insights
•	Certain venues consistently favored batting first, while others supported chasing
•	A small group of players consistently performed under pressure
•	Some bowlers combined low economy with high wicket-taking ability
