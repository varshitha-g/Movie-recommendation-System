# Movie Recommendation System

This project focuses on building a recommendation system that suggests movies to users based on their preferences. Using collaborative and content-based filtering techniques, the model provides personalized movie recommendations, enhancing the user experience for movie platforms.

## Table of Contents

Overview

Dataset

Recommendation Techniques

Technologies Used

Results

## Overview

The Movie Recommendation System is designed to recommend movies to users based on past ratings and preferences. By analyzing user data and movie attributes, the system provides personalized recommendations, combining collaborative filtering and content-based filtering approaches.

## Dataset

Source: The dataset contains user ratings, movie details, and genres.

Features: Movie ID, title, genres, user ID, and rating.

Preprocessing: Handled missing values, normalized ratings, and created features for recommendation algorithms.
## Recommendation Techniques

This project uses a combination of recommendation techniques:

Collaborative Filtering: Based on user-item interactions, using techniques like K-Nearest Neighbors (KNN) and matrix factorization.

Content-Based Filtering: Utilizes movie metadata (e.g., genres) to recommend similar movies based on user preferences.

Hybrid Model: Combines collaborative and content-based filtering for improved accuracy.
## Technologies Used

Python: For data processing and modeling.

Pandas & NumPy: For data manipulation and analysis.

Scikit-Learn: For implementing collaborative filtering algorithms.

NLTK: For text processing in content-based filtering.

Matplotlib & Seaborn: For data visualization.
## Results

Evaluation Metrics: Used metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to evaluate model performance.

Performance: Collaborative filtering combined with content-based filtering yielded the best recommendation results.
