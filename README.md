# 🎬 KNN-Movie-Recommender

This project implements a simple movie recommendation system using the K-Nearest Neighbors (KNN) algorithm and the MovieLens 100K dataset. It recommends movies to users based on the preferences of similar users.

## 📚 Table of Contents

- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Evaluation](#evaluation)
- [Report](#report)

## 🎞️ Dataset

This project uses the [MovieLens 100K Dataset](https://www.kaggle.com/datasets) which contains 100,000 ratings from 943 users on 1,682 movies.

> ⚠️ Due to licensing, the dataset is **not included** in this repository. Please download it from [Kaggle](https://www.kaggle.com/datasets) and place it in the `data/` directory.

## ✨ Features

- Loads and explores the MovieLens dataset using Pandas
- Builds a User-Item Interaction Matrix
- Implements KNN using cosine similarity
- Recommends movies based on similar users
- Evaluates recommendations with Precision and Recall
- Visualizes similarity scores and recommendation performance

- ## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/alaaashraf19/KNN-Movie-Recommender.git
   cd KNN-Movie-Recommender


## 📈 Evaluation

The recommendation system was evaluated using:

- **Precision**: Proportion of recommended movies that are relevant.
- **Recall**: Proportion of relevant movies that were recommended.

We tested different values of `k` to analyze the trade-offs.

## 📄 Report

For a detailed explanation of methodology, design decisions, and results:

👉 [Read the Full Report](./Report.pdf)
