# 🎬 Movie Box Office Revenue Prediction

This project uses machine learning to predict movie box office revenue based on various movie metadata such as budget, cast, crew, genres, and more.

## 📂 Project Structure
movie-revenue-prediction/ 
├── data/ # Datasets (raw and processed) 
├── notebooks/ # Jupyter notebooks for EDA and modeling 
├── src/ # Source code for data processing and modeling 
├── requirements.txt # Project dependencies 
├── README.md # Project documentation 
└── .gitignore # Files/folders to ignore in Git

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
