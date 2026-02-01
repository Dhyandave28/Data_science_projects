# Human Activity Recognition using SVM 📱🏃‍♂️

A Multiclass Classification project that predicts human physical activities (Walking, Sitting, Standing, etc.) using smartphone sensor data. This project implements a **Support Vector Machine (SVM)** to categorize complex motion patterns.

## 📌 Project Overview
Using the Human Activity Recognition (HAR) dataset, this project processes data captured by smartphone accelerometers and gyroscopes. The goal is to build a highly accurate classifier that can distinguish between six different human activities.

### Key Objectives
* **Multiclass Classification:** Categorizing six distinct activities: Laying, Sitting, Standing, Walking, Walking Downstairs, and Walking Upstairs.
* **Kernel Optimization:** Utilizing the Radial Basis Function (RBF) kernel in SVM to handle non-linear decision boundaries.
* **Hyperparameter Tuning:** Implementing `GridSearchCV` to find the optimal `C` and `gamma` values for the model.
* **Performance Analysis:** Evaluating the model using high-resolution confusion matrices and classification reports.



## ⚙️ How It Works
The project pipeline includes:
1. **Data Preprocessing:** Loading and shuffling the dataset to ensure unbiased training.
2. **Exploratory Analysis:** Visualizing the distribution of activities to check for class balance.
3. **Model Selection:** Building a Support Vector Classifier (SVC).
4. **Optimization:** Running an automated grid search to maximize model precision and recall across all categories.
5. **Validation:** Testing the final model on unseen data to ensure generalization.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Machine Learning:** `scikit-learn` (SVM, GridSearchCV)
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `seaborn`, `matplotlib`

## 📊 Dataset Installation
This project uses the **Human Activity Recognition with Smartphones** dataset from Kaggle.

**Dataset Link:** [Human Activity Recognition with Smartphones](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)

### Setup Instructions:
1. **Download:** Download the `train.csv` and `test.csv` files from the Kaggle link provided.
2. **Directory:** Ensure the data is in the path `/kaggle/input/human-activity-recognition-with-smartphones/` or update the path in the first code cell.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d uciml/human-activity-recognition-with-smartphones
