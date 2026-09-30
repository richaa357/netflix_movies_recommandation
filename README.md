# Netflix Movie Recommender

A recommendation system that suggests similar Netflix movies and TV shows, built with Python and machine learning.


## About
Type a Netflix title and get 10 similar titles. It uses movie details like genre, cast, director and description to find matches.

## Dataset
[Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) (about 8,800 titles)

## How it works
1. Clean the data
2. Combine genre, cast, director, country and description into one text
3. Convert text to numbers using TF-IDF and sentence embeddings
4. Find similar titles using cosine similarity

## Results
| Model | Genre hit rate@10 |
|---|---|
| TF-IDF | add your number |
| Embeddings | add your number |
| Hybrid | add your number |

## How to run
Open the notebook in Google Colab and click Runtime > Run all.

## Tools used
Python, pandas, scikit-learn, sentence-transformers, Gradio

## Author
YOUR NAME - [GitHub](https://github.com/YOUR_USERNAME)
