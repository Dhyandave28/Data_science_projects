# Pima Indians Diabetes Analysis 🩺

A detailed Exploratory Data Analysis (EDA) and visualization project focused on the Pima Indians Diabetes dataset. This project explores the diagnostic measurements to identify the strongest indicators for diabetes onset in patients.

## 📌 Project Overview
This notebook is focused on the analysis of the health records of female patients of Pima Indian heritage. The goal is to use statistical analysis and data visualization to understand how variables like Glucose levels, BMI, and Age correlate with a positive diabetes diagnosis.

### Key Objectives
* **Statistical Distribution:** Analyzing the spread and skewness of health metrics like Insulin and Blood Pressure.
* **Feature Correlation:** Identifying which medical factors have the strongest linear relationship with diabetes outcome.
* **Data Visualization:** Creating 3D scatter plots and correlation matrices to uncover hidden patterns in the data.
* **Data Cleaning:** Inspecting the dataset for missing values or unrealistic zeros (e.g., zero blood pressure or BMI).

## ⚙️ How It Works
The analysis follows a systematic data science workflow:
1.  **Data Ingestion:** Loading the dataset and performing initial checks with `.info()` and `.describe()`.
2.  **Univariate Analysis:** Creating histograms to understand the frequency distribution of individual features.
3.  **Multivariate Exploration:** Generating 3D plots to observe how three features (e.g., Glucose, BMI, and Age) interact simultaneously.
4.  **Heatmap Correlation:** Visualizing the Pearson correlation coefficients to prioritize features for future machine learning models.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib` (including `mpl_toolkits.mplot3d`), `seaborn`
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Installation
This project uses the **Pima Indians Diabetes Database** originally from the National Institute of Diabetes and Digestive and Kidney Diseases.

**Dataset Link:** [Pima Indians Diabetes Database on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

### Setup Instructions:
1. **Download:** Download `diabetes.csv` from the Kaggle link provided.
2. **Directory:** Place the file in the project root or the specified `/kaggle/input/` directory.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d uciml/pima-indians-diabetes-database
