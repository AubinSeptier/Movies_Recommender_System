# Movies Recommender System

## Introduction
This project was carried out during my internship in KMUTNB (Thailand) in my 4th year of engineering school at Polytech Dijon. I implemented various simple recommendation systems in order to understand how they work and obtain the most relevant recommendations possible. The project uses the "[The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)" dataset from Kaggle, based on the MovieLens dataset. The dataset contains metadata for 45,000 movies listed in the Full MovieLens dataset. The dataset consists of movies released on or before July 2017. The dataset also contains 26 million ratings from 270,000 users for all 45,000 movies.

## Contents
The three recommendation systems are based on the following methods:
- **Content-Based Recommender System** (Cosine Similarity Method): This method recommends movies based on the similarity of their content using the cosine similarity method and a weighted score formula.
- **Content-Based Recommender System (FNN Method)**: This method recommends movies based on the similarity of their content using a Feedforward Neural Network (FNN) model.
 - **Hybrid Recommender System (FNN Method)**: This method combines movie features and users ratings to recommend movies using a Feedforward Neural Network (FNN) model.