# Knowledge-Based Movie Recommender

A hybrid movie recommendation system combining **Prolog-based knowledge representation**, **content similarity**, and **user ratings**.

## Overview

This project implements a knowledge-based recommendation system that integrates Python with Prolog to represent movie metadata and perform rule-based reasoning.

Movie information is transformed into Prolog facts, while similarity rules are used to identify related movies. User ratings are then incorporated to generate personalized recommendation scores.

The system is evaluated on held-out rating data using standard recommendation metrics.

## Key Features

- Movie knowledge-base construction from metadata
- Prolog-based knowledge representation and reasoning
- Content-based movie similarity
- Personalized recommendations using user ratings
- Integration of Python and SWI-Prolog through PySwip
- Evaluation using Precision, Recall, and F1-score

## Technologies

- Python
- SWI-Prolog
- PySwip
- pandas
- NumPy
- scikit-learn
- Jupyter Notebook

## Project Structure

```text
knowledge-based-movie-recommender/
│
├── knowledge_based_movie_recommender.ipynb
├── db.pl
├── movies_metadata.csv
├── train_ratings.csv
├── test_ratings.csv
├── requirements.txt
└── README.md
