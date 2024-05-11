# Cinema Recommendation Engine #

# Overview
This project implements a cinema recommendation engine using Python, Pandas, scikit-learn, and ipywidgets. The goal is to help users discover movies based on their preferences and viewing history.

# Project Structure
movies.csv: CSV file containing movie data (title, genres, etc.).
ratings.csv: CSV file containing movie ratings data (userId, movieId, rating, etc.).
cinema_recommendation.ipynb: Jupyter Notebook containing the Python code for the recommendation engine.
README.md: Documentation file providing an overview of the project.

# Dependencies
pandas
scikit-learn
numpy
ipywidgets

# Usage
Open the Jupyter Notebook cinema_recommendation.ipynb.
Execute the code cells sequentially to load data, preprocess, and build the recommendation engine.
Use the interactive widget to search for movies and get recommendations based on user input.

# Features
Data cleaning: Removing special characters and irrelevant information from movie titles.
Text vectorization: Using TfidfVectorizer to convert movie titles into numerical features.
Cosine similarity: Calculating similarity scores between user input and movie titles.
Recommendation engine: Analyzing movie ratings to recommend movies based on user preferences.
Interactive widget: Creating an interactive search interface for users to discover movies.

# Future Enhancements
Personalization: Adding user profiles for personalized recommendations.
Integration: Incorporating external APIs for real-time movie data.
User feedback: Implementing a feedback system to improve recommendation accuracy.

# Credits
Pandas
scikit-learn
NumPy
ipywidgets
