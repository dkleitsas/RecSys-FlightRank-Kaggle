# Kaggle Flight Rank Recommender Systems Competition

This repository contains an entry to the [FlightRank 2025: Aeroclub RecSys Cup](https://www.kaggle.com/competitions/aeroclub-recsys-2025) Kaggle competition, focused on predicting flight rankings. It's my first attempt at a Kaggle competition and was an overall very interesting and rewarding experience (even though I didn't put as much time as I wanted into it and I'm pretty dang far from the top).

Features

- Models: LightGBM (LGBM), XGBoost, and an ensemble combining both.

- Hyperparameter Tuning: Performed with Optuna for optimized model performance.

- Feature Engineering: Extensive feature creation and transformation to improve ranking accuracy.

Model Analysis

- SHAP analysis for feature importance and interpretability.

- Error analysis to understand model weaknesses and guide feature improvements.


## Notes for future self: 
- Cross Validation with K-fold mandatory
- Try out bagging
- Tune on subset of data, it works fine enough
- Target encoding ++, but try also different types of encoding, maybe something neural to generate embeddings?
- More isn't always better
- Start with SOTA but experimenting with different ideas can also lead to gains
- Once results are out check out what top placers did
