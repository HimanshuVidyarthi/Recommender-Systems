# Recommender Systems

This repository showcases the development of movie recommendation systems using Content-Based Filtering and User-Based Collaborative Filtering techniques. The project is designed to help users receive tailored movie suggestions based on either the features of the movies themselves or similarities among user preferences.

## Project Overview

This project includes:

1. **Content-Based Filtering**: Recommends movies similar to a user's preferred titles based on metadata.
2. **User-Based Collaborative Filtering**: Uses ratings from other users with similar tastes to suggest movies.

Each method is implemented in a Jupyter notebook for an interactive, step-by-step walkthrough of the recommendation process.

## Dataset

The repository includes two primary datasets:

- **movies.csv**: Contains information about various movies, including metadata such as titles and genres.
- **ratings.csv**: Includes ratings provided by users, which is essential for implementing collaborative filtering.

Both files are necessary to execute the recommendation models effectively.

## Files

- **01. Content Based Filtering.ipynb**: Demonstrates content-based filtering, using the features of movies for recommendations.
- **User Based Collaborative Filtering.ipynb**: Demonstrates collaborative filtering based on user similarity and rating patterns.

## Prerequisites

Ensure the following libraries are installed:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

## Usage

Run the notebooks in sequence to:

1. Load the data and preprocess it for filtering.
2. Select a movie (or user) to generate recommendations based on your preferred filtering technique.
3. Analyze and interpret the results to understand the differences between the approaches.

## Results

- **Content-Based Filtering**: Offers personalized recommendations based on movie features like genre and description.
- **User-Based Collaborative Filtering**: Provides suggestions by identifying users with similar preferences.
