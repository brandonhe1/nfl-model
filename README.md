# NFL Game Winner Prediction
This notebook implements machine learning models to **predict the winners of NFL games** from Week 5 on of the 2025 NFL season, using team statistics and advanced metrics. 

**Random Forest Classifier** and **XGBoost** models were used, trained on past games to generate predictions for upcoming games. The model leverages these features:

- Points per game scored
- Points per game allowed
- Turnover differential
- 3rd down conversion % (offense & defense)
- Offensive EPA/play
- Defensive EPA/play

The models run **week-by-week**, updating rolling averages for each team and generating matchup-based features to predict the next week's outcomes. It also tracks **actual results and prediction accuracy** over the season.
