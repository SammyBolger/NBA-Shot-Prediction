# NBA-Shot-Prediction

# NBA Shot Prediction

![NBA Logo](https://upload.wikimedia.org/wikipedia/en/0/03/National_Basketball_Association_logo.svg)

Inspired by a [TED Talk on NBA analytics](https://www.ted.com/talks/rajiv_maheswaran_the_math_behind_basketball_s_wildest_moves?language=en) and a sense of nostalgia for one of my favorite NBA seasons, this project dives into the world of basketball data and machine learning. As an avid sports fan, I wanted to explore how predictive modeling could capture the randomness and rhythm of the game—and see how it’s evolved over the years.

---

## 🏀 Objective

Build a machine learning model to predict whether a given shot in the 2016–17 NBA season would result in a make or a miss, using shot-level data including player, location, shot distance, shot type, and more.

---

## 📂 Dataset

- Source: [Kaggle - NBA 2016-17 Shot Log](https://www.kaggle.com/wh0801/NBA-16-17-regular-season-shot-log)
- Local file in repo: `data/shot_log_all_teams.csv`

Example of the raw data:

![Data Preview](./data.png)

---

## 🔍 EDA (Exploratory Data Analysis)

We performed visual and statistical analysis to understand the features most associated with shot success.

- **Heatmap of Correlations**  
  ![Heatmap](./heatmap.png)

- **Shot Chart by Location**  
  ![Shot Chart](./shotchart.png)

---

## 🤖 Modeling

We experimented with several classification models to predict shot outcomes:

- Logistic Regression  
  ![Logistic Regression](./logisticregression.png)

- Naive Bayes  
  ![Naive Bayes](./naivebayes.png)

- Random Forest  
  ![Random Forest](./randomforestclassifier.png)

**Best model:** Random Forest  
**Accuracy:** ~67%

---

## 🎯 Conclusion

Despite tuning and testing various models, results plateaued around 66–67% accuracy. This may reflect the unpredictable nature of basketball, where even perfect shots don’t always fall.

Future features that could improve performance include:

- Shot clock time
- Closest defender’s distance and identity
- Passes leading to shot
- Shot contest level
- Player fatigue or streaks

---

## 🧠 Applications

While the theoretical accuracy ceiling may not exceed ~85% due to randomness in the game, models like this still offer value in:

- Team strategy simulations
- Fantasy sports projections
- Betting markets

---

## 🚀 How to Run

1. Clone the repo  
   `git clone https://github.com/SammyBolger/NBA-Shot-Prediction`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Run the notebook  
   `NBA_Shot_Prediction.ipynb`

---

## 📈 Future Work

- Integrate defender tracking data (SportVU)
- Use sequence models (RNNs) for dynamic shot prediction
- Deploy a web dashboard for interactive exploration

---

## 📬 Contact

- **LinkedIn:** [Sam Bolger](https://www.linkedin.com/in/sambolger/)
- **Email:** [sbolger@cord.edu](mailto:sbolger@cord.edu)

---
