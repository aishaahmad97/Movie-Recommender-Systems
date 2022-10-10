# Movie-Recommender-Systems
The need for reliable and efficient recommender systems is increasing with an increased amount of data. Many companies such as Google, Netflix, Facebook, Amazon, ...etc. use recommender systems to provide a personalized experience to their users. This enables users to get engaged with your products which boosts customer engagements and drives revenues to new heights.

# Dataset:
> MovieLens 1M movie ratings. Stable benchmark dataset. 1 million ratings from 6000 users on 4000 movies. Released 2/2003. *You can find the original dataset [here](https://grouplens.org/datasets/movielens/1m/).*

All ratings are contained in the file "ratings.dat" and are in the
following format: UserID::MovieID::Rating::Timestamp

- UserIDs range between 1 and 6040 
- MovieIDs range between 1 and 3952
- Ratings are made on a 5-star scale (whole-star ratings only)
- Timestamp is represented in seconds since the epoch as returned by time(2)
- Each user has at least 20 ratings.

Movie information is in the file "movies.dat" and is in the following
format: MovieID::Title::Genres

- Titles are identical to titles provided by the IMDB (including
year of release)
- Genres are pipe-separated and are selected from the following genres:
Action|Adventure|Animation|Children's|Comedy|Crime|Documentary|Drama|Fantasy|Film-Noir|Horror|Musical|Mystery|Romance|Sci-Fi|Thriller|War|Western
