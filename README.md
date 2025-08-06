# Movie-Recommendation-System
Movie-Recommendation-System using 100K MovieLens dataset and cosine similarity

This project is a **User-Based Collaborative Filtering Recommendation System** using the **MovieLens 100K dataset**.

It recommends movies for users based on **cosine similarity** between user ratings, and evaluates performance using **Precision@K**.



##  Dataset
- Dataset: [MovieLens 100K](https://grouplens.org/datasets/movielens/100k/)
- Preprocessed into a *user–item matrix* (users as rows, movies as columns)



##  Methodology
1. *Data Loading & Cleaning* – Remove NaNs, replace with 0
2. *User–Item Matrix Creation* – Pivot table of users vs. movies
3. *Similarity Calculation* – Cosine similarity between users
4. *Recommendation* – Suggest top-N movies from most similar users
5. *Evaluation* – Precision@K using hidden relevant movies
