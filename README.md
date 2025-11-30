# EPL Match Predictions

This project uses **data science and machine learning** to predict **English Premier League (EPL)** match outcomes.

It combines:
- Football statistics such as (GF, GA, xG, xGA, form, etc.)
- Probability models like the **Poisson** and **Skellam** distributions
- Machine learning algorithms for more advanced predictions

The goal is to build a **reusable prediction pipeline** that can:
1. Collect and clean EPL data  
2. Engineer meaningful features that affects the outcome of football matches 
3. Predict win / draw / loss probabilities and possibly expected goals  
4. Export results for **analysis, visualisation and deployment**

## Features

- **Data Cleaning & Preprocessing**
  - Handles raw league tables and match data
  - Cleans team names, missing values, and formats
  - Merges home & away stats
  
- **Explore and Analyse the data through descriptive statistics
  - Use the measure of central tendency
  - Use visualisation techniques such as Histogram and Bar Charts
  - Plot and visualise shot and passing networks

- **Feature Engineering**
  - Goals For / Against (GF, GA)
  - Goal Difference (GD)
  - Expected Goals (xG, xGA, xGD, xGD_per_90)
  - Last 5 games form: wins, draws, losses, points, form score
  - Home vs Away strength

- **Prediction Engine**
  - **Poisson goal model** for predicting scorelines
  - **Skellam distribution** for modelling goal difference
  - Match outcome probabilities:
    - P(Home Win), P(Draw), P(Away Win)

Machine Learning
  - ML models (e.g. Logistic Regression, Random Forest, XGBoost) can be added
  - Uses engineered features as inputs
  - Predicts match result or goal counts






