# Yelp Review Sentiment Classification

Comparing machine learning models for star rating classification of Yelp reviews.

## Overview

This project performs sentiment analysis on Yelp reviews, classifying them by polarity (positive/negative). Using a dataset of over 7 million Yelp reviews, we compare several ML approaches to determine which most accurately predicts star ratings from review text alone.

## Dataset

The [Yelp Open Dataset](https://www.yelp.com/dataset) contains 7M+ reviews including review IDs, restaurants, food categories, funny/cool/useful tags, and 1–5 star ratings. For this project, we stripped accessory features and used only the written review text and star ratings.

## Models

| Model | Description |
|-------|-------------|
| **Naive Bayes** | Probabilistic baseline classifier |
| **Random Forest** | Ensemble tree-based classifier |
| **CNN** | Convolutional Neural Network for text classification |
| **VADER & TextBlob** | Lexicon-based sentiment analysis |

## Project Structure

```
├── CNN.ipynb                # CNN model training and evaluation
├── In Progress CNN.ipynb    # CNN development notebook
├── RandomForestModel.ipynb  # Random Forest and Naive Bayes models
├── data_loader.py           # Data cleaning and preprocessing
├── imports.py               # Shared imports across notebooks
```

## Tools & Libraries

- **Pandas** — data manipulation
- **PyTorch** — CNN implementation
- **Scikit-learn** — traditional ML models and evaluation metrics
- **NLTK** — text preprocessing and NLP utilities
- **Matplotlib** — visualization

## Future Work

- **Keyword extraction** — Identify words driving sentiment polarity via word clouds and regression analysis, then use those features to improve preprocessing and model accuracy.
- **Lexicon fine-tuning** — Apply ML to adjust sentiment lexicon polarity weights using the labeled training data.

## Contributors

- [eitanlaredo](https://github.com/eitanlaredo)
- [CowAvenge](https://github.com/CowAvenge) 
- [nadia424](https://github.com/nadia424)
