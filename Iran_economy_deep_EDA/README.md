# Iran Economy: 6-Decade Macroeconomic Analysis 🇮🇷📈

A comprehensive deep-dive into Iran's economic history spanning over sixty years. This project provides a full macroeconomic story, highlighting long-term trends, structural shifts, and economic anomalies through data visualization and statistical analysis.

## 📌 Project Overview
This notebook analyzes Iran's economic trajectory from 1960 to the present. By examining indicators such as GDP, inflation, and trade, the project aims to visualize how historical events and policy changes have shaped the nation's financial landscape.

### Key Objectives
* **Macroeconomic Storytelling:** Mapping more than six decades of data to identify structural shifts in the economy.
* **Trend Identification:** Visualizing growth patterns, periods of hyperinflation, and economic volatility.
* **Data Cleaning & Reshaping:** Handling long-term time-series data and ensuring consistency across different eras.
* **Feature Visualization:** Using advanced plotting to correlate different economic indicators (GDP vs. Inflation, etc.).

## ⚙️ How It Works
The analysis follows a structured macroeconomic research workflow:
1.  **Data Ingestion:** Loading a multi-decade dataset and performing initial structural audits.
2.  **Time-Series Analysis:** Examining yearly changes in key indicators to pinpoint specific years of economic disruption or growth.
3.  **Visual Analytics:** Creating clear, informative line charts and distribution plots to show the evolution of the Iranian Rial and national output.
4.  **Anomaly Detection:** Highlighting specific "outlier" years that correspond to major historical or global economic shifts.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Installation
This project utilizes the **Iran Economy Dataset** available on Kaggle, covering indicators from 1960 onwards.

**Dataset Link:** [Iran Economy Dataset (1960-2023)](https://www.kaggle.com/datasets/mhassansaboor/iran-economic-indicators-1960-2024)

### Setup Instructions:
1. **Download:** Download `iran_economy.csv` (or the equivalent file) from the Kaggle link provided.
2. **Directory:** Place the file in your project root or the `/kaggle/input/` folder.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d mreza0/iran-economy-dataset-19602023
