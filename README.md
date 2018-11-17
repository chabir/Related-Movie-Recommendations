# Related-Movie-Recommendations

The goal of this project is to find related movies using the Movielens 20M dataset.

Here, the goal is to build a model / code that orders movies based on their "relatedness" using the MovieLens
20M dataset (https://grouplens.org/datasets/movielens/20m/) which contains over 20 thousands movie titles. We will frame the problem
regarding the “relatedness” of movies and after exploring the dataset, we will show different
approaches to propose an ordered list of movies given a particular one.

To say that two movies are related can be interpreted in many ways: the similarity in the titles, the
description, the genres, the year range, the popularity or the ratings relative to one-another is one way
to define the relatedness between movies.

In this exercise, we will try to explore quickly the dataset, propose some features for relatedness and
explore different techniques that I discovered over the last few days during my readings.

The code was developed in python on an AWS EC2 instance.
