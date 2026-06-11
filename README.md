🎬 Movie Recommendation System

A Content-Based Movie Recommendation System built using Python, Machine Learning, and Streamlit. The application recommends movies similar to a selected movie by analyzing genres, keywords, cast, crew, and movie overviews using Natural Language Processing (NLP) techniques.

 🚀 Features

* Recommend movies similar to a selected movie
* Display movie posters using TMDB API
* Content-based filtering approach
* Interactive Streamlit web interface
* Fast recommendations using precomputed cosine similarity

 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* NLTK
* Streamlit
* TMDB API

* 📊 Dataset

This project uses the TMDB 5000 Movie Dataset containing:

* Movie metadata
* Genres
* Keywords
* Cast information
* Crew information
* Movie overviews

Files used:

* tmdb_5000_movies.csv
* tmdb_5000_credits.csv

* ⚙️ How It Works

1. Merge movie and credits datasets.
2. Extract important features:

   * Genres
   * Keywords
   * Top Cast Members
   * Director
   * Overview
3. Create a combined text feature called "tags".
4. Apply text preprocessing and stemming.
5. Convert text into vectors using CountVectorizer.
6. Compute Cosine Similarity between movies.
7. Recommend the most similar movies.

* 📂 Project Structure

Movie_Recommendation_System/

├── app.py

├── movie_recommender_system.py

├── tmdb_5000_credits.csv

├── .gitignore

└── README.md



