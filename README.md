# cricketworldcup-2023-bowling-stats-prediction-using-data-science

# Cricket World Cup 2023 – Bowling Stats Prediction

## 📌 Overview
This project uses **data science** techniques to predict bowling performance in the ICC Cricket World Cup 2023.  
By analysing historical match data, player statistics, and contextual match factors, the model forecasts key bowling metrics such as:
- Wickets per match
- Total tournament wickets
- Economy rate

## 📂 Dataset
- **Source:** Kaggle / ESPNcricinfo / Cricbuzz (ball-by-ball and match-level stats)
- **Files:**
  - `matches.csv` – match-level metadata
  - `deliveries.csv` – ball-by-ball events
  - `bowling.csv` – player bowling summaries

## 🛠 Features
- Recent form: wickets & economy in last N matches
- Career averages & strike rates
- Opposition batting strength
- Venue & pitch statistics
- Match conditions (toss, innings, overs bowled)

## 📊 Methodology
1. **Data Cleaning & Preprocessing** – Handle missing values, format dates, encode categorical features.
2. **Feature Engineering** – Create statistical and contextual predictors.
3. **Model Training** – Poisson regression, XGBoost, or Random Forest for count predictions.
4. **Evaluation** – MAE, RMSE, and rank correlation.
5. **Prediction** – Output per-match and tournament-level forecasts.

## 🚀 Installation
```bash
git clone https://github.com/<your-username>/cwc2023-bowling-prediction.git
cd cwc2023-bowling-prediction
pip install -r requirements.txt
▶ Usage
bash
Copy
Edit
python predict.py --input data/ --output results/
Or run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook cwc2023_bowling_prediction.ipynb
📈 Example Output
Bowler	Predicted Wickets	Predicted Economy
Player A	18.4	4.95
Player B	16.2	5.12

📜 License
MIT License – free to use and modify.

🙌 Acknowledgements
Kaggle dataset contributors

ESPNcricinfo for cricket statistics

ICC Cricket World Cup 2023 coverage









Ask ChatGPT
