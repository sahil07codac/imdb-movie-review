# IMDB MOVIE REVIEW 
![image](https://github.com/sahil07codac/imdb-movie-review/assets/141804728/e31f88ba-0353-459b-9c0d-07269466082f)

# About Dataset

This IMDB dataset goal is to provide a base for sentiment analysis. Usually, datasets of this kind provide binary classes telling whether the text is positive or negative however this approach fails in some points. We don't know how the data was linked to those labels and the queries used. Here, these fails were solved. To do so we:

Query ratings using a fixed window of 1 point to increase the probability of having reviews rating that specific value.
Checked whether the movie was already evaluated or not.
Recorded the firsts reviews and ratings excluding the spoiler tag.
Then after data being retrieved, we translated all reviews to Portuguese.
Just as in the original IMDB Dataset, we didn't retrieve a huge amount of reviews from the same movie to keep a low correlation of reviews. We recommend pre-processing this dataset in order to have a more uniform distribution of ratings.


# skills -PYTHON, ML, NLTK, SENTIMENTAL ANALYSIS TOOL


# Steps Followed

Data Preparation: Preprocess the raw dataset, handle missing values, and engineer relevant features.
EDA:
Model Training: Train the machine learning models using historical data and tune hyperparameters if necessary.
Model Evaluation: Evaluate the trained models using appropriate evaluation metrics and visualize the results.
Prediction: Make predictions for future windfarm power output based on the trained models 
