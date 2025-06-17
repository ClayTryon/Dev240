# COVID-19 High Fatality Classification

Author: Clay Tryon

## Project Description
This project analyzes COVID-19 statistics by country to determine which factors are most predictive of a country having a high case fatality rate (CFR). The goal is to classify whether a country's fatality rate is considered high based on features such as total confirmed cases, deaths, recoveries, active cases, and recent changes. The dataset was obtained from a Kaggle COVID-19 global statistics repository.

The project explores and evaluates several classification models to identify the strongest predictors and determine the most accurate model for this imbalanced classification problem.

## Machine Learning Algorithms Used
- Decision Tree Classifier (with hyperparameter tuning)
- Random Forest Classifier (with class balancing and tuning)
- XGBoost Classifier (with scale_pos_weight adjustment and tuning)

## Machine Learning Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
