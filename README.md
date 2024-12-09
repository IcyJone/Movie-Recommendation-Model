# Movie-Recommendation-Model
  This project implements a movie recommendation system using both content-based and collaborative filtering approaches.

# Datasets
  [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
  
  [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=ratings_small.csv)

These datasets provide essential movie data such as titles, overviews, cast, crew, genres, and user ratings. Both datasets are used in this project to build the recommendation system

# Features
  Content-Based Filtering: Recommends movies based on metadata such as overviews, cast, crew, genres, and keywords.
  
  Vectorization: Uses TF-IDF and CountVectorizer to process text data.
  
  Similarity Measurement: Calculates cosine similarity for movie recommendations.
  
  Collaborative Filtering: Predicts user ratings for movies using the Surprise library with SVD (Singular Value Decomposition). Evaluated with RMSE and MAE using     cross-validation.

  Popularity-Based Ranking: Highlights top-rated and frequently voted movies using a weighted rating formula.

# How It Works
  Data Preprocessing:
  Merges and cleans datasets.
  Extracts features such as directors, top cast, genres, and keywords.

  Content Recommendations:
  Generates recommendations using metadata and cosine similarity.

  Collaborative Recommendations:
  Utilizes user ratings to predict preferences with matrix factorization (SVD).

# Dependencies
  Python (Pandas, NumPy, Matplotlib, Scikit-learn, Surprise)

# Usage
  1.  Clone the repository.
  2.  Download the required datasets from Kaggle and place them in the appropriate directory.
  3.  Run the provided code to explore recommendations.

