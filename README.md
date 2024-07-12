# Movie Recommendation System Project

## Overview

This project develops a movie recommendation system based on cosine similarity. It consists of three main notebooks:

1. **Text Wrangling**
2. **Feature Engineering**
3. **Training and Get Movies Recommendation Function**

The dataset used in this project can be found on Kaggle:
[The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset/data)

## Notebooks

### 1. Text Wrangling

This notebook focuses on pre-processing the numeric data and merging the datasets from the provided Kaggle link. The main tasks include:

- Fixing contractions and possessive apostrophes
- Removing stopwords
- Stemming

### 2. Feature Engineering

In this notebook, we perform feature engineering on the cleaned data. The tasks include:

- Standardizing numeric features
- Applying TF-IDF
- Combining features

### 3. Training and Get Movies Recommendation Function

This notebook trains the recommendation system and provides a function to get movie recommendations. The tasks include:

- Calculating cosine similarity to generate the similarity matrix

## How to Run

### To Retrain the Data

1. **Run the notebooks in the following order:**
   1. Text Wrangling
   2. Feature Engineering
   3. Training and Get Movies Recommendation Function

### To Get Movie Recommendations with Trained Data

1. Use the already processed similarity matrix.
2. Use the provided function to get movie recommendations based on one movie you like.

## Next Steps

- Add more recent movies to the dataset.

## Requirements

- `nltk`
- `contractions`

Make sure to install the required packages using pip:

```bash
pip install nltk contractions
```

## Conclusion

This project demonstrates a complete pipeline for building a movie recommendation system, from data wrangling to generating recommendations. The modular design allows for easy retraining and updating with new data.

