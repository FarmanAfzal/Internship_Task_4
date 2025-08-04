# 🎬 Movie Rating Prediction using Regression

This project builds a machine learning model to predict how a user would rate a movie they haven’t watched, using a regression-based approach.

## 📊 Dataset

The project uses the [MovieLens](https://grouplens.org/datasets/movielens/) dataset:
- `ratings.csv` (userId, movieId, rating, timestamp)
- `movies.csv` (movieId, title, genres)

## 🧠 Methodology

- Preprocess and clean the dataset
- Compute user and movie average ratings
- Use Linear Regression to train a model
- Evaluate using RMSE and MAE

## ✅ Requirements

Install the required packages using:

```bash
pip install pandas numpy scikit-learn
