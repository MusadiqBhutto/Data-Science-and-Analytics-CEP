# Data Science & Analytics - CEP

![image](https://github.com/MusadiqBhutto/IPL-Score-Predictor/assets/88616911/aa496ffd-8211-4253-9aba-09411b143449)


**Project Title:** IPL Score Predictor

**Project Objective:** Predicting IPL Cricket Match Scores

**Overview:** In this project, our goal is to develop a machine learning model that can accurately predict the total score of an ongoing Indian Premier League (IPL) cricket match. We will create a user-friendly Python application that leverages this model to provide real-time score predictions based on the current stats of the game.

# Project Details

**Input Data:** The application will take various statistics and details of the current IPL match as input to make predictions. These inputs include:
  - **Batting Team:** Selection of the team currently at bat.
  - **Bowling Team:** Selection of the opposing bowling team.
  - **Current Over:** The over currently in progress.
  - **Current Runs:** The number of runs scored up to the current over.
  - **Wickets Taken:** The number of wickets fallen up to the current over.
  - **Runs in Last 5 Overs:** Runs scored in the last 5 overs.
  - **Wickets in Last 5 Overs:** Wickets taken in the last 5 overs.

**Machine Learning Model:** We will develop and train a machine learning model using historical IPL match data. This model will learn to analyze the provided inputs and predict the total score a team is likely to achieve by the end of the innings.

**Algorithms used:**
  - Linear Regression
  - K-Nearest Neighbor Regressor
  - XGBoost Regressor
  - RandomForest Regressor
  - SVR
  - Decision Tree Regressor

**Dataset:** The dataset comprises of over by over details of matches and runs from 2008 to 2020.

**Dataset Used:** ipl_data.csv

  - mid - match id
  - date - when matches are played
  - venue - place where matches aew played
  - bat_team - batting team
  - bowl_team - bowling team
  - batsman - batsman
  - bowler - bowler
  - runs - runs scored
  - wickets - wickets
  - overs - overs - next 3 are based on this
  - run_last_5 - runs scored in last 5 overs
  - wicket_last_5 - wickets in last 5 overs
  - stricker - batsman playing as main 1
  - non-striker - batsman playing as runner up - not main 0
  - total - total score (target variable)

**User-Friendly Interface:** To make score predictions accessible to cricket enthusiasts, we will create a simple and stylish Python application. The interface will allow users to select the participating teams, enter live match statistics, and receive real-time score predictions.

![image](https://github.com/MusadiqBhutto/IPL-Score-Predictor/assets/88616911/bcda3163-2257-4eac-810b-ba23dcc839cd)


**Prediction Range:** The application will provide a predicted score range, indicating the expected total score with a certain margin of error. This range helps users understand the uncertainty associated with the prediction.

**Conclusion:** By combining machine learning techniques with a user-friendly interface, our project aims to enhance the cricket-watching experience by providing viewers with insightful score predictions. This tool will assist cricket fans, analysts, and enthusiasts in making informed assessments of ongoing IPL matches, adding an exciting dimension to the game.




