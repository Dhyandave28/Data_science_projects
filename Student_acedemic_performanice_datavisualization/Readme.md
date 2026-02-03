# Student Academic Performance Visualization 🎓📊

A comprehensive data visualization project focused on identifying the socio-economic and behavioral factors that influence student academic success. This project uses descriptive analytics to uncover patterns in educational outcomes.

## 📌 Project Overview
Academic performance is rarely determined by studying alone. This notebook explores a variety of factors—including gender, nationality, place of birth, and stage of education—to see how they correlate with student achievement levels (Class).

### Key Objectives
* **Demographic Analysis:** Visualizing the distribution of students by gender and nationality.
* **Academic Behavioral Study:** Examining the relationship between educational stages (Primary, Middle, High School) and final academic performance.
* **Performance Classification:** Visualizing how students are categorized into "Low", "Medium", and "High" performance tiers.
* **Categorical Data Visualization:** Utilizing Seaborn and Matplotlib to create intuitive count plots and distribution charts.

## ⚙️ How It Works
The project follows a clean data visualization workflow:
1.  **Data Ingestion:** Loading the student performance dataset and inspecting the feature types.
2.  **Univariate Analysis:** Creating count plots to understand the demographic makeup of the student body.
3.  **Bivariate Exploration:** Comparing academic "Class" (performance) against categorical variables like Gender and Stage.
4.  **Insight Extraction:** Identifying which demographic groups or educational stages show higher concentrations of top-performing students.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Installation
This project uses the **Student Academic Performance** dataset available on Kaggle.

**Dataset Link:** [Student Academic Performance Dataset](https://www.kaggle.com/datasets/neurocipher/student-performance)

### Setup Instructions:
1. **Download:** Download the CSV file from the Kaggle link provided.
2. **Directory:** Place the file in your project root or the specified `/kaggle/input/` directory.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d aljarah/xAPI-Edu-Data
