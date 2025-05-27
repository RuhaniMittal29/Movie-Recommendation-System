# Movie Recommendation System 🍿🎬

## Table of Contents
- [Introduction](#introduction)
- [Approach and Methodology](#approach-&-methodology)
- [Technology Stack](#technology-stack)

##Introduction

In the age of digital entertainment, discovering the right movie from thousands of options can be overwhelming. A Movie Recommendation System simplifies this process by analyzing movie metadata to suggest films tailored to a user's interests.

This project focuses on building a content-based recommendation system that provides personalized movie suggestions based on similarities in attributes such as genres, cast, director, and keywords. The system uses cosine similarity to identify and recommend movies that are closely related to a given title.

The project uses the IMDb 5000 Movies Dataset from ([Kaggle](https://www.kaggle.com/code/thedevastator/imdb-5000-movies-multiple-genres-dataset](https://www.kaggle.com/datasets/rakkesharv/imdb-5000-movies-multiple-genres-dataset )), which includes detailed metadata such as movie titles, genres, directors, cast, plot keywords, and ratings. The dataset provides both categorical and quantitative information, offering a rich base for building a robust recommendation engine.

## Approach & Methodology

- Utilized the IMDb 5000 Movies Dataset from Kaggle, which includes details like genres, directors, cast, and more.
- Cleaned and preprocessed the data to handle missing values and unify formatting.
- Extracted meaningful features from textual metadata such as genres, keywords, and cast.
- Used TF-IDF vectorization to numerically represent text-based attributes.
- Calculated cosine similarity scores between movies to determine closeness.
- Developed a function that, given a movie title, returns the top N most similar movies.

## Technology Stack
- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation and cleaning
  - `seaborn`, `matplotlib` – Data visualization and exploratory analysis
  - `scikit-learn` – Specifically `cosine_similarity` for measuring similarity between movies
- **Development environment**: Jupyter Notebook

This project demonstrates the application of content-based filtering, and similarity metrics to build an effective recommendation system using real-world movie data.


