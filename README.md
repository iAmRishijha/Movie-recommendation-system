# Movie-recommendation-system
## Overview
This Movie Recommendation System is built using cosine similarity to provide movie recommendations based on various features, including movie overviews, genres, keywords, cast, and directors. The system analyzes these features to find similarities between movies and generate personalized recommendations for users.

## Features
Movie Overview: The system analyzes movie overviews to understand the plot and themes of each movie.

Genres: The genre information helps in grouping movies with similar themes or styles.

Keywords: Keywords associated with each movie provide additional insights into their content.

Cast: The cast of a movie can influence its similarity to other movies with the same actors or actresses.

Director: Directors often have a unique style, and movies directed by the same person may have similarities.

## Data Source
Link - https://drive.google.com/file/d/1cCkwiVv4mgfl20ntgY3n4yApcWqqZQe6/view

## Dependencies
Python

Numpy

Pandas

Scikit-learn

## Implementation
The recommendation system is implemented using the following steps:

Data Preprocessing: The dataset is cleaned and prepared for analysis, including removing duplicates, handling missing values, and formatting the data.

Vectorizaton: converting text data into vectors for implementing cosine similarity method.

Cosine Similarity: Cosine similarity is calculated for each pair of movies based on their features (overview, genres, keywords, cast, director).

User Preferences: Users can input their faviourate movie name.

Recommendation Generation: The system recommends movies that are most similar to the user's preferences by sorting movies based on cosine similarity scores.
