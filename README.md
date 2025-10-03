# NFL Game Winner Prediction
This notebook implements two machine learning models to **predict the winners of NFL games** from Week 5 on of the 2025 NFL season, using team statistics and advanced metrics. 

**XGBoost** and **Random Forest Classifier** were used, trained on past games to generate predictions for upcoming games. These models leverage features such as:

- Points per game scored
- Points per game allowed
- Turnover differential
- 3rd down conversion % (offense & defense)
- Offensive EPA/play
- Defensive EPA/play

Every week, the notebook is ran to update cumulative statistical averages for each team and generating matchup-based features to predict the next week's outcomes. It also tracks **actual results and prediction accuracy** over the season.
