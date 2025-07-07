✅ Movie Recommendation System This repository contains a machine learning project that builds and compares multiple collaborative filtering models for personalized movie recommendations using the MovieLens 100K dataset.
The project includes data preprocessing, similarity-based modeling, matrix factorization, model evaluation, and saving the trained models.

📁 Dataset Source: MovieLens 100K

Description: 100,000 movie ratings from 943 users on 1,682 movies

Target: Predict ratings and recommend top unseen movies
📊 Models Compared

✅ User-Based Collaborative Filtering

Uses cosine similarity between users

Recommends based on similar users' preferences

✅ Item-Based Collaborative Filtering

Uses cosine similarity between items (movies)

Suggests similar movies to those the user already liked

✅ SVD (Matrix Factorization)

Trained using Surprise library

Predicts unseen ratings

Evaluated with RMSE and MAE

🔧 Features Data preprocessing and exploration

User-Item matrix creation

Cosine similarity (users and items)

SVD model training

Model evaluation using:

Precision@K

RMSE, MAE

Merge predictions with movie titles

Save trained models using pickle
📦 Requirements
pandas, numpy, scikit-learn, matplotlib, seaborn, scikit-surprise, pickle

📈 Sample Results
Model	Metric	Score
User-Based CF	Precision@5	0.20
SVD (Surprise)	RMSE	0.9355
MAE	0.7374
SVD Recommendations	Top movie	Close Shave, A (1995) — ★ 4.91
📊 Result Summary
The User-Based model showed reasonable performance in cold-start cases

The SVD model gave better prediction accuracy overall (RMSE ≈ 0.93)

Item-Based filtering helped identify similar movies effectively

Model saving and reusability implemented

📌 License
This project is intended for educational and research purposes as part of the Elevvo Pathways ML Internship.






