# Capstone-Project-2

## Sentiment analysis of Tweets about the movie Joker

### About
Out in the USA beginning of October 2019 and throughout theaters in the world later on, no doubt that Joker has divided its audience. Whether people love or hate it, the reactions were numerous. I saw it myself at the movies in Switzerland as soon as it came out, and felt exactly this way: divided. The movie received a Golden Lion win at the Venice Film Festival, I had high expectations. The complex personality of the Joker was one of the reasons I wanted to see the movie. But after visioning it, I realized it had a strong impact on me, more than expected and not only positive. The critics I read afterwards were also two-folds, both positive and negative. Therefore, I thought it would be interesting to train a classification model on Tweets on the topic of Joker.

### Steps
The steps that we will follow to perform the sentiment analysis are:

- acquiring a Test set
- acquiring and preparing a Training set
- pre-processing tweets in both Test set and Training set
- building a vocabulary/list of words in our training data set
- matching tweet content against our vocabulary
- building our word feature vector
- training the classifier
- testing the model
- evaluating the model performance

### Requirements
- Twitter API
- Niek Sanders' Corpus csv file (https://github.com/karanluthra/twitter-sentiment-training/blob/master/corpus.csv)
