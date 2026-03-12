# Рекомендательная система фильмов

## Data
The dataset `MovieLens` was taken from [here](https://grouplens.org/datasets/movielens/32m/)

Structure:

<img width="365" height="376" alt="Снимок экрана 2026-03-12 в 18 40 00" src="https://github.com/user-attachments/assets/09575130-4761-4635-8d65-e859b2da7b60" />

## Models

### 1. Baseline (Popular)

Precision@50 = 0.0547

MAP@50 = 0.0106

### 2. User-based
The users-ratings matrix is being built. Cosine similarity is used

Precision@50 = 0.2478

MAP@50 = 0.0819

NDCG@50 = 0.6051

### 3. Item-based
The users-ratings matrix is being built. Cosine similarity is used

Precision@50 = 0.1320

MAP@50 = 0.0365

NDCG@50 = 0.4165

### 4. SVD
Precision@50 = 0.2037

MAP@50 = 0.0562

NDCG@50 = 0.5969

### 5. Clusterization(KMeans)
Precision@50 = 0.3343

MAP@50 = 0.0132

NDCG@50 = 0.8622

## Best Model
Clusterization(KMeans)
