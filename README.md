Content Based Movie Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get 
the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

Link to youtube demo: https://www.youtube.com/watch?v=dhVePtyECFw.

've developed a similar application called "The Movie Cinema" which supports all language movies. But the only thing that differs from this application is that I've used the TMDB's recommendation engine in
"The Movie Cinema". The recommendation part developed by me in this application doesn't support for multi-language movies as it consumes 200% of RAM (even after deploying it to Heroku) for generating Count Vectorizer 
matrix for all the 700,000+ movies in the TMDB.

Don't worry if the movie that you are looking for is not auto-suggested. Just type the movie name and click on "enter". You will be good to go eventhough if you made some typo errors.

