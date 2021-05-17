# Movie Recommendation With PySpark
The objective of this project was to develop a Collaborative filtering Recommendation System that would predict a Users rating for new movies that haven't been rated yet based off of other similar users. Using an ALS algorithm to finally generate 10 movies recommendation that new user may like.
## Data
[MovieLens Dataset](https://grouplens.org/datasets/movielens/)

"This dataset (ml-latest-small) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users between March 29, 1996 and September 24, 2018. This dataset was generated on September 26, 2018.

Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

The data are contained in the files links.csv, movies.csv, ratings.csv and tags.csv. More details about the contents and use of all these files follows.

This is a development dataset. As such, it may change over time and is not an appropriate dataset for shared research results. See available benchmark datasets if that is your intent.

This and other GroupLens data sets are publicly available for download at http://grouplens.org/datasets/." Via [MovieLens README](https://files.grouplens.org/datasets/movielens/ml-latest-small-README.html)

## Google CoLab
For anyone trying to replicate/improve/study this notebook [CLICK HERE](https://colab.research.google.com/drive/1XKl7ZltZOK3NBizV1KaEUsgTSlmCf5Zo)

## Future Work and Areas of Improvement
- Using the bigger dataset provided by grouplens
- Implement a Content-Based Filtering 
- Improve model by running CrossValidator/ParamGridBuilder

