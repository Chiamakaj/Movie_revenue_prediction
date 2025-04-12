# 🎬 Movie Box Office Revenue Prediction

This project uses machine learning to predict movie box office revenue based on various movie metadata such as budget, cast, crew, genres, and more.

## 📂 Project Structure
movie-revenue-prediction/
├── data/
│   ├── raw/                        # Raw datasets (e.g., from TMDB or Kaggle)
│   └── processed/                  # Cleaned & transformed data
├── notebooks/
│   ├── EDA.ipynb                   # Exploratory data analysis
│   └── modeling.ipynb              # Model training and evaluation
├── src/
│   ├── data_preprocessing.py       # Scripts to clean and preprocess data
│   ├── model.py                    # Model training and saving
│   └── predict.py                  # Script to run predictions on new data
├── requirements.txt                # Python dependencies
├── README.md                       # Project description and setup
└── .gitignore

## 🔍 Problem Statement

Given metadata about a movie, can we accurately predict how much revenue it will generate at the box office?

## 📊 Dataset

- **Source**: [TMDB 5000 Movie Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- **Fields**: Title, Genre, Budget, Release Date, Cast, Crew, Popularity, Runtime, and more.

## 📌 Goals

- Perform exploratory data analysis (EDA)
- Clean and preprocess data
- Engineer features for model input
- Train multiple regression models
- Evaluate model performance
- (Optional) Deploy as a simple web app
