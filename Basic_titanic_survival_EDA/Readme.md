# Titanic Survival: Complete EDA & Prediction 🚢

A comprehensive Exploratory Data Analysis (EDA) and Machine Learning project focused on the infamous Titanic shipwreck. This project explores passenger demographics and uses Logistic Regression to predict survival outcomes.

## 📌 Project Overview
The sinking of the Titanic is one of the most infamous shipwrecks in history. While there was some element of luck involved in surviving, certain groups (such as women, children, and upper-class passengers) were more likely to survive than others.

### Key Objectives
* **Exploratory Data Analysis (EDA):** Visualizing patterns and correlations between passenger features (Age, Sex, Class) and survival.
* **Data Cleaning:** Handling missing values in the `Age`, `Cabin`, and `Embarked` columns.
* **Feature Engineering:** Preprocessing categorical data for machine learning compatibility.
* **Predictive Modeling:** Building a baseline Logistic Regression model to predict passenger survival.

## ⚙️ How It Works
The project follows a structured data science pipeline:
1. **Missing Value Analysis:** Utilizing heatmaps to visualize gaps in the data (particularly the high percentage of missing `Cabin` information).
2. **Statistical Profiling:** Using `describe()` and `info()` to understand the distribution of fares, ages, and passenger classes.
3. **Data Splitting:** Partitioning the data into training and validation sets using `train_test_split`.
4. **Model Evaluation:** Measuring performance using Accuracy Scores, Confusion Matrices, and Classification Reports (Precision, Recall, F1-Score).

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Libraries:** * `pandas` & `numpy` (Data Processing)
    * `matplotlib` & `seaborn` (Data Visualization)
    * `scikit-learn` (Machine Learning & Metrics)

## 📊 Dataset Installation
This project uses the official Titanic dataset from Kaggle. 

**Dataset Link:** [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)

### Setup Instructions:
1. **Download:** Get `train.csv` and `test.csv` from the link above.
2. **Directory:** Place the files in a folder named `/kaggle/input/titanic/` (or update the file path in the notebook).
3. **Kaggle API:**
   ```bash
   kaggle competitions download -c titanic
