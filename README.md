## Movie Recommendation System

This project implements a movie recommendation system using machine learning algorithms and various modules to provide personalized movie recommendations based on user preferences. The dataset includes tags such as genres, keywords, taglines, cast, and directors, which are utilized to create recommendation models.

# Features

1.Dataset: Utilizes a dataset containing movie information including genres, keywords, taglines, cast, and directors.

2. Machine Learning Algorithms: Implements machine learning algorithms such as cosine similarity, TF-IDF vectorization, and collaborative filtering for recommendation tasks.

 Modules Used:
  1. cosine_similarity: Calculates the similarity between movies based on their features.
  2.TfidfVectorizer: Transforms text data into numerical vectors for machine learning.

3.Recommendation Storage: Stores recommended movies along with user information in an SQL database for future reference.

# Dataset Structure
The dataset used in this project contains the following tags:
1. genres: Movie genres (e.g., Action, Comedy, Drama).
2. keywords: Keywords related to the movie's plot, themes, etc.
3. tagline: Catchphrases or slogans associated with the movie.
4. cast: Actors and actresses appearing in the movie.
5. director: Director(s) of the movie.

# Project Structure
1. Data Preprocessing: Cleanses and prepares the dataset for machine learning tasks, including handling missing values and encoding categorical features.
2. Feature Extraction: Extracts relevant features such as genres, keywords, and cast information from the dataset.
3. Model Training: Trains recommendation models using machine learning algorithms and similarity measures.
4. Recommendation Generation: Generates personalized movie recommendations based on user preferences and historical data.
5. Database Integration: Stores recommended movies and user information in an SQL database for future retrieval.

# Usage
1. Clone the repository: git clone https://github.com/viksith/movie_recommendation.git
2. Install dependencies
3. Generate recommendations: Run python main.py
   
