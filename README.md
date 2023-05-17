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


## Key insights
Most of the reviews are predominantly positive

Sentiment of NSW listings are very positive

Negative and positive sentiments words share similar words

Difficult for model to identify negative words due to scarcity of negative training data

Machine learning model requires fine tuning


### Some of the results
**Overall listing Ratings scaled to 0-100**
<img width="719" alt="image" src="https://github.com/MellowPhi/Airbnb-Sentiment-Analysis/assets/48370987/f50ee446-deb2-47e1-a750-697cc12b74c6">
Majority of the listings have high ratings


**Common words used: Word cloud**
![image](https://github.com/MellowPhi/Airbnb-Sentiment-Analysis/assets/48370987/da108934-41a7-49e8-bff6-e9ce58b68cdd)

**Histo plot of the most frequent words**
<img width="769" alt="image" src="https://github.com/MellowPhi/Airbnb-Sentiment-Analysis/assets/48370987/cd3ad646-936d-46c0-a049-0f4068135310">


**Positive sentiment word frequency**
<img width="803" alt="image" src="https://github.com/MellowPhi/Airbnb-Sentiment-Analysis/assets/48370987/7fef17f1-bf0e-449c-ae10-ab2c79932ccf">

**Negative sentiment word frequency**
<img width="807" alt="image" src="https://github.com/MellowPhi/Airbnb-Sentiment-Analysis/assets/48370987/4a950cc8-63ab-4a01-8e6a-759c7bf199fa">



## How to run
I recommend creating a `conda` env and running. Will be posting the `requirements.txt` for all the dependicies for this project soon.

## Notes 
The dataset exceeds the 100mb Github limit, so I will be putting up an external link to the original dataset used for this analysis

## To do
- Add `requirements.txt`
- Add the link to the original dataset.

