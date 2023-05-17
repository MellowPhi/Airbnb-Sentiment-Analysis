# Airbnb-Sentiment-Analysis

## Summary of the analysis
This analysis used two datasets listings.csv and reviews.csv.

Prliminary data exploring done on listings.csv to understand general sentiment of the listings.
Data cleaning: i.e removing empty cells and invalid data value
Initial word cloud generated to gain an overview of the reviews.
Sentiment analysis using VADER and produce negative and positive sentiment dataframe
Generate word clouds of negative and positive sentiments. Bar plots of most frequent word for negative sentiment showed that most non-english reviews are marked as negative sentiments
Data cleaning again: use of langdetect library to filter out english reviews
Performed sentiment analysis on CLEANED data and generate a refined dataset
Logsitic regression is used to train a model using the refined labeled dataset (Vectorised the review column and sentiment are labeled target for model training)
Topic Modelling using LDA and NMF

## How to run
I recommend creating a `conda` env and running. Will be posting the `requirements.txt` for all the dependicies for this project soon.

## Notes 
The dataset exceeds the 100mb Github limit, so I will be putting up an external link to the original dataset used for this analysis

## To do
- Add `requirements.txt`
- Add the link to the original dataset.

