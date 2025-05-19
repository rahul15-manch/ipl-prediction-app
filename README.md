# 🏏 IPL Match Winner Prediction System

This project is a Machine Learning-based IPL Match Winner Prediction System designed to forecast the likely winner of an Indian Premier League (IPL) cricket match based on historical and live input data. It utilizes data science techniques and predictive modeling to provide match outcome predictions.
# 📖 About the Project

The IPL Prediction System analyzes match details such as teams, venue, toss decision, and key player stats to predict the outcome of a match. The goal is to apply data analytics and machine learning to real-world sports prediction and demonstrate the power of data-driven decision-making.

---

## 🛠 Tech Stack

- **Python** – Core programming language
- **Pandas, NumPy** – Data preprocessing
- **Scikit-learn** – Model training and evaluation
- **Streamlit** – Web-based user interface
- **Matplotlib / Seaborn** – Data visualization
- **Jupyter Notebook / VS Code** – Development environments

---

## ✨ Features

- Predict match winners based on input features
- User-friendly web interface (via Streamlit)
- Displays prediction confidence level
- Interactive filters for team selection, venue, etc.
- Visual insights and EDA on IPL datasets

---

## ⚙️ How It Works

1. Data is loaded and cleaned using Pandas.
2. Important features (like toss decision, team names, and venue) are extracted.
3. A classification model (e.g., Logistic Regression) is trained on historical IPL match data.
4. The model predicts the probable winner of a match based on user inputs.
5. The interface displays the prediction and confidence score.

---

## 📊 Dataset

- Source: Kaggle IPL Datasets 
- Features used:
  - Team 1 & Team 2
  - Toss Winner
  - Toss Decision
  - Match Venue
  - Match Date
  - Winning Team

## Install required libraries:
pip install -r requirements.txt

## Run the Streamlit app:
streamlit run app.py

▶️ Usage
-Launch the app using the command above.
-Select the two teams, toss winner, venue, and decision.
-Click "Predict" to see the predicted winner.


🚀 Future Scope
-Add live match data scraping and real-time prediction
-Deploy the model using AWS/GCP or Heroku
-Integrate with cricket APIs (e.g., Cricbuzz, ESPN)
-Improve accuracy using advanced ensemble models
-Add player-level performance factors and weather impact

Live Link:https://ipl-prediction-app-jnqcdr3th4ywbg7mnj6ums.streamlit.app/















