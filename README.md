# Recommender-System-Practical-Data-Science-
This project was deployed as the Assignment 3 of the COSC2670 - Practical Data Science course. It implements and compares different recommendation system approaches using the MovieLens 1M dataset. The implementation includes KNN Collaborative Filtering and Matrix Factorization techniques, with a focus on performance evaluation and comparison.

## Overview

The project consists of three main tasks:
1. KNN-based Collaborative Filtering
2. Matrix Factorization using SVD
3. Ranking-based Evaluation and Comparison

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Surprise
- Matplotlib
- Seaborn

## Install required packages:
```bash
pip install numpy pandas scikit-learn surprise matplotlib seaborn


## Dataset: The MovieLens 1M dataset is used, containing:

1,000,209 ratings
6,040 users
3,900 movies
Rating scale: 1-5

Implementation Details
Task 1: KNN-based Collaborative Filtering

User-based collaborative filtering
Parameters tested:

k values: [5, 10, 20, 50, 100]
Similarity metrics: Cosine Similarity and Pearson Correlation


Evaluation using RMSE

## Task 2: Matrix Factorization

SVD implementation
Model improvements:

Reduced factors (30)
Increased regularization (0.06)
Extended training epochs (30)
Optimal learning rate (0.005)



Task 3: Ranking-based Evaluation

Train-Test Split: 80%-20%
Metrics: AP and NDCG
Comparison of both approaches

Results
Key findings:

KNN optimal performance: RMSE = 0.8771 (k=100)
SVD improved performance: RMSE from 1.0123 to 0.9971
Ranking evaluation:

KNN: AP=0.8597, NDCG=0.9669
SVD: AP=0.8755, NDCG=0.9746



