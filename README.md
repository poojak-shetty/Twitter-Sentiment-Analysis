# Twitter-Sentiment-Analysis
It is a Natural Language Processing Problem where Sentiment Analysis is done by Classifying the Positive tweets from negative tweets by machine learning model for text analysis, data analysis and data visualization.
# Introduction
Natural Language Processing (NLP) is a hotbed of research in data science these days and one of the most common applications of NLP is sentiment analysis.It is used all over from opinion polls to creating entire marketing strategies.

Thousands of text documents can be processed for sentiment (and other features including named entities, topics, themes, etc.) in seconds, compared to the hours it would take a team of people to manually complete the same task.

We will do so by following a sequence of steps needed to solve a general sentiment analysis problem. We will start with cleaning of the raw text of the tweets. Then we will explore the cleaned text and try to get some intuition about the context of the tweets. After that, we will extract numerical features from the data and finally use these feature sets to train models and identify the sentiments of the tweets.

This is one of the most interesting challenges in NLP!
# About the Dataset
The dataset is taken from **Kaggle**

The link to the dataset is [TWITTER-SENTIMENT-ANALYSIS](https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech?select=test.csv)

It has 2 files,
* Train dataset
  * This dataset has 3 features:ITEMID,LABEL(0 AND 1) AND TWEET. 
* Test Dataset
  * This dataset has 2 features:ITEMID AND TWEET.
  
## Problem Statement
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label ‘1’ denotes the tweet is racist/sexist and label ‘0’ denotes the tweet is not racist/sexist, your objective is to predict the labels on the given test dataset.
# The Project
Now lets get to my project. It has all the parts in the same notebook.
* DATA PROCESSING AND CLEANING.
  * If we skip this step then there is a higher chance that you are working with noisy and inconsistent data.
  * The objective of this step is to clean those  which are less relevant to find the sentiment of tweets such as punctuation, special characters, numbers, and terms which don’t carry much weightage in context to the text.
* VISUALIZATION.
  * What are the most common words in the entire dataset? What are the most common words in the dataset for negative and positive tweets, respectively?Well,these questions are answered here.
* EXTRACTING FEATURES AND TRAINING.
  * We explore the cleaned dataset and extract features using Bag-of-Words and TF-IDF.
  * We have also trained the cleaned dataset using Keras model.
  * We have predicted the labels of test dataset too.
 ##### THE LINK TO THIS PROJECT IS [TWITTER SENTIMENT ANALYSIS](https://colab.research.google.com/drive/19JIPeV2YErhZLDOCNfwU0icZT4BWRVaX?usp=sharing)
 # CONCLUSION
After using Natural Language Processing Techniques in this project , I would like to conclude that twitter is a good reflection of sentiment in our society.We get all information from breaking news and entertainment to sports and politics.Here,we have successfully detected hate speech in tweets using the Keras model which gave validation accuracy of 94%.Therefore,we could successfully do natural language processing and get the desired output(twitter sentiment analysis) from the tweets.Finally,we have learned how to approach sentiment analysis problems having raw data .
 
