# Cardiovascular Disease Dataset EDA 🏥

An in-depth Exploratory Data Analysis (EDA) of Cardiovascular Disease (CVD) data. This project focuses on summarizing cohort characteristics, inspecting clinical and lifestyle feature distributions, and identifying key risk factors for heart disease.

## 📌 Project Overview
Cardiovascular diseases are a leading cause of mortality worldwide. This notebook serves as a foundation for risk modeling by performing a rigorous analysis of the factors that contribute to heart health.

### Key Objectives
* **Data Profiling:** Understanding the distribution of age, gender, and physical characteristics (height/weight) in the dataset.
* **Clinical Analysis:** Examining the impact of blood pressure (systolic/diastolic) and cholesterol levels on CVD risk.
* **Lifestyle Correlation:** Analyzing how smoking, alcohol consumption, and physical activity relate to cardiovascular health.
* **Data Cleaning:** Handling outliers (especially in blood pressure readings) and ensuring data integrity for modeling.

## ⚙️ How It Works
The analysis is broken down into several key stages:
1.  **Missing Value & Outlier Detection:** Identifying and correcting unrealistic values in the dataset (e.g., extreme blood pressure values).
2.  **Feature Engineering:** Creating new metrics like **BMI (Body Mass Index)** to better assess health risks.
3.  **Bivariate & Multivariate Analysis:** Using boxplots and countplots to see how different categories (like smokers vs. non-smokers) differ in disease prevalence.
4.  **Correlation Mapping:** Using heatmaps to find the strongest predictors of cardiovascular disease.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Installation
This project utilizes the Cardiovascular Disease dataset available on Kaggle.

**Dataset Link:** [Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/ahmeduzaki/cardiovascular-disease-risk-assessment-dataset)

### Setup Instructions:
1. **Download:** Download the `cardio_train.csv` file from the link above.
2. **Directory:** Place the CSV file in your project root or a `/data/` folder.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d sulianova/cardiovascular-disease-dataset
