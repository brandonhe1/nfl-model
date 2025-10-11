# 🏈 NFL Game Winner Prediction

This project uses **machine learning** to **predict the winners of NFL games** starting from **Week 5 of the 2025 season**, leveraging advanced statistical and analytical features.

It applies **cumulative team metrics** to simulate how teams evolve week-by-week and evaluates two predictive models.

---

## ⚙️ Overview

Using current season data, the notebook trains and evaluates two models:

- 🌲 **Random Forest Classifier (RFC)**
- 🔥 **XGBoost Classifier (XGB)**

These models learn from past matchups to forecast future game outcomes, continuously improving as new weekly data is added.

---

## 📊 Features Used

Each matchup is represented using **team-level performance metrics** and **advanced statistics**, including:

- 🏆 **Points per Game (PPG) Scored**
- 🧱 **Points per Game Allowed**
- 🔄 **Turnover Differential**
- ⛓️ **3rd Down Conversion % (Offense & Defense)**
- ⚡ **Offensive EPA/play** (Expected Points Added per play)
- 🛡️ **Defensive EPA/play**

---

## 🔁 How It Works

1. **Collects** data for all games up to the current week  
2. **Computes cumulative averages** for each team  
3. **Builds matchup-based features** (home vs. away comparisons)  
4. **Trains** both Random Forest and XGBoost models on historical data  
5. **Predicts** winners and win probabilities for upcoming games  
6. **Evaluates** week-by-week prediction accuracy  

---

## 📈 Output

- ✅ **Predicted winners** and **win probabilities** for each matchup  
- 📅 **Weekly accuracy tracking** for both RFC & XGB models  
- 🧠 **Feature importance visualization** to interpret model behavior  

---

## 🚀 Future Improvements

- 📊 Incorporate **DVOA** and **success rate** metrics  
- 🤕 Add **injury and roster impact** data  
- 🖥️ Build a **live Power BI or Streamlit dashboard** for visualization  
- ⚔️ Experiment with **ensemble and deep learning models**

---

Would you like me to add a short **“Installation & Usage”** section next (so people can clone and run your notebook directly on GitHub)?  
