# netflix-movie-recommendation
This project is a content-based movie recommendation system built using Netflix movie data. It recommends similar movies based on genre, cast, and description using Natural Language Processing (NLP) techniques.

# How It Works
Combines movie genres, cast, and descriptions
Converts text into numerical vectors using TF-IDF
Computes similarity between movies using Cosine Similarity
Recommends top N similar movies
Supports case-insensitive and typo-tolerant search

# Tech Stack
Python
Pandas, NumPy
Scikit-learn
TF-IDF Vectorization
Cosine Similarity
Fuzzy Matching
Jupyter Notebook

# Project Structure
netflix-movie-recommendation/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_recommender.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

# How to Run
pip install -r requirements.txt
jupyter notebook
Open:
notebooks/netflix_recommender.ipynb

# Example Usage
recommend("Inception")
recommend("incepcion")  # typo supported

# Key Learnings
Text preprocessing & feature engineering
TF-IDF vectorization
Similarity-based recommendation systems
End-to-end data science project workflow

# Future Improvements
User-based collaborative filtering
Streamlit web application
Hybrid recommendation system

# Author
Priyanka Konda
Data Scientist
