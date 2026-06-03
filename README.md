# Steam Game Recommender System

## Project Overview

This project develops a game recommendation system using collaborative filtering and Apache Spark MLlib.

The aim is to recommend Steam games to users based on historical interaction data, including purchases and gameplay activity. The project uses the Alternating Least Squares (ALS) algorithm to model user preferences from implicit feedback data.

The analysis was implemented in Databricks using PySpark, Spark MLlib and MLflow for experiment tracking.

## Dataset

The project uses the Steam 200K dataset, which contains user interactions with games.

The dataset includes:

- User ID
- Game title
- Action type
- Interaction value

The data represents implicit feedback rather than direct user ratings, making it suitable for collaborative filtering.

## Objectives

- Load and inspect Steam user interaction data
- Clean and prepare user-game interaction records
- Transform user and game identifiers for machine learning
- Build an ALS recommendation model
- Evaluate model performance using RMSE
- Compare different model configurations
- Track experiments using MLflow
- Generate personalised game recommendations

## Technologies Used

- Apache Spark
- PySpark
- Spark MLlib
- Databricks
- MLflow
- Python
- Pandas
- Matplotlib

## Machine Learning Method

The recommendation model was developed using Alternating Least Squares (ALS), a collaborative filtering algorithm commonly used for recommender systems.

The project used implicit feedback modelling because the dataset contains user actions such as purchasing and playing games rather than explicit star ratings.

## Results

Several ALS model configurations were tested and compared.

The best models achieved RMSE values around 0.38 to 0.39, showing that the model was able to capture useful patterns in user-game interactions.

## Skills Demonstrated

- Recommendation Systems
- Collaborative Filtering
- Apache Spark
- PySpark
- Machine Learning
- Feature Engineering
- Model Evaluation
- MLflow Experiment Tracking
- Big Data Processing

## Files Included

- Databricks notebook export
- Model development workflow
- ALS recommendation system implementation

## Author

Mohammad Reza Haghighatju

MSc Data Science Graduate  
University of Salford
