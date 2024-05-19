# IPL Winning Team Prediction

This project is a simple Streamlit web application that predicts the probability of winning for two IPL teams based on various input parameters. The prediction model is built using machine learning, and the application allows users to input specific match details to get the win probability for the batting and bowling teams.

## How to Use

1. *Select Teams:* Choose the batting and bowling teams from the provided list of IPL teams.
2. *Select Host City:* Pick the host city for the match from the available cities.
3. *Input Match Details:* Enter the target score, current score, overs completed, and wickets out.
4. *Predict Probability:* Click the "Predict Probability" button to get the win probabilities for the selected teams.

## Setup and Installation

1. Clone the repository:

   bash
   git clone https://github.com/your-username/ipl-win-predictor.git
   

2. Run the Streamlit application:

   bash
   streamlit run app.py
   

## Model Information

The machine learning model used for prediction is stored in a pickled file (pipe.pkl). It is loaded during the application runtime.