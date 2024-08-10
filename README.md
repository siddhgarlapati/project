# Movie Recommender System

This is a content-based movie recommender system built using Streamlit and The Movie Database (TMDb) API. The application recommends movies based on a selected movie title and displays their posters.

## Features

- Recommend movies based on a selected movie title.
- Display movie posters for the recommended movies.
- Simple and interactive web interface using Streamlit.


I have utilized the TMDB dataset, which contains information on approximately 5,000 movies. After preprocessing the data, I extracted several features, including the movie overview, genre, keywords, top three cast members, and the director from the crew. I then identified the top 5,000 most frequently used words across these features.

Using these words, I vectorized the data and trained a recommendation model. When a user searches for a movie, the model displays the top 5 most similar movies along with their posters.

