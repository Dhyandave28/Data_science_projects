# Movie Recommendation System 🎬

A Content-Based Basic Movie Recommendation System built with Python using the MovieLens dataset. This project analyzes movie genres to suggest films similar to a user's choice using Basic's of Natural Language Processing (NLP) and vector similarity.

**Dataset Link:** [MovieLens Dataset on Kaggle](https://www.kaggle.com/datasets/ayushimishra2809/movielens-dataset)

### How to set up the dataset:
1.  **Manual Download:**
    * Visit the link above and download the zip file.
    * Extract `movies.csv` and `ratings.csv` into a folder named `data/` in your project directory.
    
2.  **Using Kaggle API:**
    If you have the Kaggle API installed, you can download it using:
    ```bash
    kaggle datasets download -d nicoletacilibiu/movies-and-ratings-for-recommendation-system
    ```

3.  **Update File Paths:**
    Ensure the paths in your notebook match your local file structure:
    ```python
    movies = pd.read_csv('data/movies.csv')
    ratings = pd.read_csv('data/ratings.csv')
    ```

## 📌 Project Overview
This system implements **Content-Based Filtering**. It takes a movie title as input, analyzes its genre characteristics, and ranks other movies in the dataset based on how similar their content is to the input.

### Features
* **Data Visualization:** Uses WordClouds to visualize frequent genres and movie titles.
* **Text Vectorization:** Implements `TfidfVectorizer` to convert movie genres into numerical vectors.
* **Similarity Scoring:** Uses `linear_kernel` (Cosine Similarity) to calculate the distance between movie profiles.
* **Top-N Recommendations:** Returns the most relevant movie matches based on the highest similarity scores.

## ⚙️ How It Works
The recommendation engine follows these steps:
1. **Preprocessing:** Extract and clean movie genres and titles from the MovieLens dataset.
2. **TF-IDF Calculation:** Transforms the "genres" text into a TF-IDF (Term Frequency-Inverse Document Frequency) matrix to weigh the importance of different genres.
3. **Cosine Similarity:** Computes a similarity matrix where every movie is compared against every other movie.
4. **Ranking:** When a movie is searched, the system fetches its similarity row, sorts the scores, and displays the top matches.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Data Handling:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (TfidfVectorizer, linear_kernel)
* **Visualization:** `matplotlib`, `wordcloud`

## 📊 Dataset
The project uses the **MovieLens dataset**, which includes:
* `movies.csv`: Contains `movieId`, `title`, and `genres`.
* `ratings.csv`: Contains `userId`, `movieId`, `rating`, and `timestamp`.
* Total Movies: ~10,329
* Total Ratings: ~105,339

## 🚀 Getting Started
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/movie-recommendation-system.git](https://github.com/Dhyandave28/Data_science_projects/new/main/Basic_movie_recommendation_system.git)

2. **Install dependencies:**
    pip install pandas matplotlib wordcloud scikit-learn

3. **Run the Notebook:**
   Open movie-recommendation-system.ipynb in Jupyter or VS Code to see the engine in action.
