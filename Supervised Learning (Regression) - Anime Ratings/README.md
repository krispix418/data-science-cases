## Context
Streamist is a streaming platform that hosts anime series and movies worldwide. Every title is rated by viewers, and the platform tracks engagement metrics like watch count, drop rate, and want-to-watch lists.

## Objective
- Identify the key factors that influence anime ratings
- Build a linear regression model to predict a title's average user rating
- Assess model performance and interpret feature importance

## Key Questions
1. What are the most important factors influencing anime ratings?
2. How well can viewer behavior and anime metadata predict ratings?

## Techniques Used
- Exploratory data analysis and feature engineering
- Linear regression
- Regularization (Ridge, Lasso)
- Model evaluation: R², RMSE, MAE
- Hyperparameter tuning

## Dataset
`anime_data_raw.csv` — anime metadata including media type, episode count, duration, studio, tags/genres, and user engagement metrics (watched, watching, dropped, want-to-watch, votes, rating)
