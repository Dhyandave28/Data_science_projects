# World's Top 100 Tallest Buildings Analysis 🏙️🌍

A data-driven exploration of global architectural marvels. This project performs Exploratory Data Analysis (EDA) on the world's 100 tallest buildings to uncover geographic trends, structural patterns, and historical construction milestones.

## 📌 Project Overview
As cities reach higher into the sky, the distribution of "supertall" skyscrapers has shifted globally. This notebook analyzes the heights, locations, and functions of these structures to identify which countries and cities are leading the vertical race.

### Key Objectives
* **Geographic Distribution:** Identifying which countries and cities host the highest concentration of the top 100 tallest buildings.
* **Height Analysis:** Visualizing the distribution of building heights and identifying statistical outliers.
* **Architectural Trends:** Analyzing the relationship between a building's location and its architectural characteristics.
* **Stacked Visualizations:** Using stacked bar charts to compare city-level distributions across different countries.

## ⚙️ How It Works
The project follows a standard EDA pipeline:
1.  **Data Cleaning:** Managing the dataset to ensure city and country names are standardized.
2.  **Aggregation:** Grouping buildings by `Country` and `City` to measure urban density.
3.  **Advanced Plotting:** Utilizing stacked bar charts with custom colormaps (`tab20`) to visualize complex categorical data clearly.
4.  **Metric Analysis:** Calculating the frequency of buildings per region to find architectural hotspots.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Dataset Installation
This project uses the **Top 100 Tallest Building in the World** dataset available on Kaggle.

**Dataset Link:** [Top 100 Tallest Building in the World](https://www.kaggle.com/datasets/hammadfarooq470/top-100-tallest-buildings-worldwide
)

### Setup Instructions:
1. **Download:** Download the dataset CSV from the Kaggle link provided.
2. **Directory:** Place the file in your project root or the specified `/kaggle/input/` directory.
3. **Kaggle API:**
   ```bash
   kaggle datasets download -d mreza0/top-100-tallest-building-in-the-world
