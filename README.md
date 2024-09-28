# Movie Recommender System

## Overview
This project is a Movie Recommender System that suggests movies based on user preferences. By analyzing movie ratings and similarities, it provides personalized recommendations to users.

## Features
- Loads movie ratings and movie details from online datasets.
- Merges datasets to create a comprehensive view of movie ratings.
- Calculates average ratings and number of ratings for each movie.
- Provides recommendations based on user input.

## Technologies Used
- Python
- Pandas
- NumPy

## Dataset
The project uses two datasets:
1. **ratings.csv**: Contains user ratings for movies.
2. **movies.csv**: Contains movie titles and genres.

These datasets are loaded from the following links:
- [Ratings Dataset](https://raw.githubusercontent.com/kueyram/DSC630/main/Data/ratings.csv)
- [Movies Dataset](https://raw.githubusercontent.com/kueyram/DSC630/main/Data/movies.csv)

## How It Works
1. The code loads the datasets into Pandas DataFrames.
2. It merges the ratings and movies datasets based on `movieId`.
3. It calculates the mean rating and count of ratings for each movie.
4. A user-item matrix is created, allowing for similarity calculations.
5. The user can input a movie title and specify how many recommendations they want.
6. The system returns a list of similar movies based on correlation values.

## How to Run
1. Make sure you have Python installed on your machine.
2. Install the required libraries:
   pip install pandas numpy
3. python movie_recommender.py

Example

To get recommendations, you can enter a movie title, such as "Forrest Gump (1994)," and specify the number of movies you'd like to receive as recommendations.
Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request.
