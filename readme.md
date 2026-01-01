IPL Best XI Analysis Dashboard (Power BI)
Project Overview

This project focuses on selecting a Best XI team using historical IPL data through data-driven analysis.
The dashboard evaluates batsmen, bowlers, and all-rounders based on performance metrics such as runs, strike rate, wickets, and economy-related indicators.

The objective is to move beyond reputation-based selection and instead use impact-focused analytics.

Dashboard Components
Batsmen Analysis
-Total runs scored by each batsman
-Strike rate comparison
-Role-based classification (Top Order / Middle Order)

Top performers highlighted using Top N filters

-Economy vs Strike Rate (Impact Analysis)
-Scatter plot showing relationship between:
-Batting Strike Rate
-Bowling Economy

Helps identify high-impact players who balance scoring speed with bowling efficiency
All-Rounder Evaluation
Combined score derived from:
Batting Score
Bowling Score

Ensures selection of multi-skill impact players

Final dashboard selects only the best-performing all-rounder

🎯 Bowling Unit Analysis

Total wickets taken

Overs bowled

Bowling strike rate

Wicket contribution visualized through bar and pie charts

Key Insights:-

-High run scorers are not always the most impactful — strike rate matters
-All-rounders provide balance only when both skills contribute meaningfully
-Bowling attack selection prioritizes wicket-taking ability over volume

Tools & Technologies Used
-Python (Pandas, NumPy) – Data cleaning & feature engineering
-Power BI – Data modeling, DAX measures & visualization
-CSV datasets – Processed IPL ball-by-ball & match data

Project Structure
data/
 ├── raw/
 ├── processed/
 │    ├── best_xi_batsmen.csv
 │    ├── best_xi_bowlers.csv
 │    └── best_xi_allrounders.csv
dashboard/
 └── IPL_Best_XI.pbix

final dashboard 
![Visual](final dash board.PNG)

