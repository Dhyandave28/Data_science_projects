# NBA Team & Context Analysis 🏀📊

A comprehensive Exploratory Data Analysis (EDA) of NBA performance data. This project dives deep into player statistics, team dynamics, and game context—including a unique analysis of referee influence on game scoring.

## 📌 Project Overview
This project aims to uncover hidden patterns in professional basketball by analyzing diverse datasets including player performance, team metrics, and external context variables.

### Key Objectives
* **Player & Team Profiling:** Analyzing scoring efficiency and contribution across different teams.
* **Contextual Analysis:** Investigating how non-player factors (like specific Referees) correlate with total points per game.
* **Data Visualization:** Creating intuitive bar plots and relationship graphs to compare top-tier performers.
* **Insight Generation:** Finding consistent or contradictory relations between game roles and performance variables.



## ⚙️ How It Works
The analysis follows a structured sports analytics workflow:
1.  **Data Ingestion:** Loading large-scale NBA datasets and inspecting feature consistency.
2.  **Referee Impact Study:** Aggregating data to see if specific referees are associated with higher or lower-scoring games.
3.  **Top-K Filtering:** Focusing on the "Top 15" entities (Teams/Referees) to make visualizations actionable and clear.
4.  **Correlation Inspection:** Testing the hypothesis that game roles have a consistent relationship with performance metrics.

## 🛠️ Tech Stack
* **Language:** Python 3.11
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Installation
This project utilizes the **NBA Dataset (Team & Context)** available on Kaggle.

**Dataset Link:** [NBA Dataset: Team & Context](https://www.kaggle.com/datasets/double0x2/nba-analytics-dataset-players-teams-and-context)

### Setup Instructions:
1. **Download:** Download the CSV files (Team and Context data) from the Kaggle link provided.
2. **Directory:** Place the files in your project root or the specified `/kaggle/input/` directory.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d mreza0/nba-dataset-team-and-context
