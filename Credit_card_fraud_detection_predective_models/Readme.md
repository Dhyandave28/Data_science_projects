# Credit Card Fraud Detection: Predictive Modeling 💳🛡️

A comprehensive machine learning project focused on detecting fraudulent credit card transactions. This project addresses the challenge of extreme class imbalance and evaluates multiple high-performance gradient boosting models to maximize detection accuracy.

## 📌 Project Overview
Fraud detection is a critical application of machine learning in finance. In this dataset, fraudulent transactions represent only **0.172%** of the total data. This notebook explores the effectiveness of various ensemble methods in identifying these rare but high-impact events.

### Key Objectives
* **Handling Imbalanced Data:** Implementing strategies to train models on datasets where the target class is extremely rare.
* **Comparative Model Benchmarking:** Evaluating five different predictive models: Random Forest, AdaBoost, CatBoost, XGBoost, and LightGBM.
* **Metric Optimization:** Using Area Under the Curve (AUC) and Confusion Matrices rather than simple accuracy to measure success.
* **Feature Understanding:** Analyzing PCA-transformed numerical features to determine transaction patterns.



## ⚙️ How It Works
The project follows a rigorous predictive modeling pipeline:
1.  **Exploratory Data Analysis (EDA):** Visualizing the heavy skew in the dataset and checking feature correlations.
2.  **Data Splitting:** Partitioning data into Training, Validation, and Test sets to prevent data leakage.
3.  **Model Training:** Implementing advanced boosting libraries:
    * **XGBoost:** Utilizing early stopping and validation sets.
    * **LightGBM:** Implementing cross-validation for robust performance estimation.
    * **CatBoost:** Testing categorical-optimized boosting performance.
4.  **Evaluation:** Comparing models based on their AUC scores and ability to minimize false negatives.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Machine Learning:** `scikit-learn`, `XGBoost`, `LightGBM`, `CatBoost`
* **Visualization:** `matplotlib`, `seaborn`, `plotly`
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Installation
This project uses the **Credit Card Fraud Detection** dataset.

**Dataset Link:** [Credit Card Fraud Detection on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### Setup Instructions:
1. **Download:** Download `creditcard.csv` from the Kaggle link provided.
2. **Directory:** Place the file in your project root or the `/kaggle/input/` folder.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d mlg-ulb/creditcardfraud


   
