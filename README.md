# IMDB MOVIE REVIEW 

**About Dataset

This IMDB dataset goal is to provide a base for sentiment analysis. Usually, datasets of this kind provide binary classes telling whether the text is positive or negative however this approach fails in some points. We don't know how the data was linked to those labels and the queries used. Here, these fails were solved. To do so we:

Query ratings using a fixed window of 1 point to increase the probability of having reviews rating that specific value.
Checked whether the movie was already evaluated or not.
Recorded the firsts reviews and ratings excluding the spoiler tag.
Then after data being retrieved, we translated all reviews to Portuguese.
Just as in the original IMDB Dataset, we didn't retrieve a huge amount of reviews from the same movie to keep a low correlation of reviews. We recommend pre-processing this dataset in order to have a more uniform distribution of ratings.
