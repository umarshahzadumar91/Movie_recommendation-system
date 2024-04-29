# Content-Based-Movie-Recommender-System
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.



It is an extension from the project:[https://github.com/umarshahzadumar91/Movie_recommendation-system](https://github.com/umarshahzadumar91/Movie_recommendation-system)

The Dataset is taken from a kaggle [kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data
).

# Results
* recommend('Avatar')
1. The Helix... Loaded
2. Krull
3. The Host
4. Apollo 18
5. Teenage Mutant Ninja Turtles III
