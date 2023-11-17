# T20 Score Predictor
Overview
This project is a T20 cricket score predictor that uses XGBoost for machine learning and Streamlit for building a user-friendly web application. The model is trained to predict the final score of a T20 cricket match based on various input features.

Features
Batting Team: Select the team batting.
Bowling Team: Select the team bowling.
City: Select the city where the match is being played.
Current Score: Input the current score in the match.
Overs Done: Input the number of overs bowled.
Wickets Out: Input the number of wickets fallen.
Runs in Last 5 Overs: Input the runs scored in the last 5 overs.

Model Training
The machine learning model is built using XGBoost. The training script and dataset are not included in this repository. You can train the model using your own dataset and update the pipe.pkl file.

Project Structure
app.py: The main Streamlit application script.
pipe.pkl: The trained XGBoost model saved as a pickle file.
requirements.txt: List of project dependencies.

Data Sources
Dataset: https://www.kaggle.com/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s
