# IMBD Sentiment Analysis

![IMDB](https://upload.wikimedia.org/wikipedia/commons/6/69/IMDB_Logo_2016.svg)

This repo contains a simple experiment of Sentiment Analysis using the IMBD dataset. The dataset contains 50,000 reviews of movies, 25,000 for training and 25,000 for testing. The reviews are labeled as positive or negative.

## Model

The model used is a simple Naive Bayes classifier based on a bag-of-words approach. For all the details check the notebook `main.ipynb`.

## Results

This model, despite its semplicity, is able to achieve pretty good results. Of course, some limitations include the impossibility of understanding the context of a word (e.g. "not good" is considered positive). It can be used for sure as a baseline for more complex models.
