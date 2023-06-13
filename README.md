# ChatGPT Tweets 

## About the Project 

ChatGPT is a popular and fast growing artificial intelligence program that has the ability to to assist and converse with humans in natural language. With the growing number of users, there have been different responses to the AI, with some praising ChatGPT highly while others have raised criticism and concerns. The goal of our project is to use sentiment analysis to classify ChatGPT tweets as Positive, Negative, or Neutral from the timeframe November 2022 (when the software first launched) to January 2023. We use a supervised approach to classify the tweets, which include Support Vector Machines (SVM) and Naive Bayes (NB). Our results found that   SVM provides higher accuracy results compared to NB when analyzing sentiment analysis for 50 thousand tweets, though NB performed better percentage wise when predicting negative sentiment rather than positive or neutral sentiment. 

## Data 

Data 

In order to classify ChatGPT tweets using Naive Bayes classifier (NB) and Support Vector Machines (SVMs), we used two datasets from Kaggle, an open source data platform. Dataset 1 pre-labeled ChatGPT tweets as positive, negative, and neutral. The dataset contains tweets on #ChatGPT which were collected from twitter over the span of a month and labeled by a sentiment analysis performed by a few developers. Dataset 1 consists of the following information: Index, Tweet, and Label, where the total number of tweets were 217,622. Dataset 2 was a collection of unlabeled tweets containing #ChatGPT from the timespan November 2022 to February 2023. This dataset consisted of the following information: Date, Tweet, Url, UserName, UserCreated, UserVerified, UserFollowers, UserFriends, Retweet, Likes, Location, and UserDescription. Dataset 2 had a total of 473,687 tweets, and in our training and testing we only kept the following information to remain consistent with Dataset 1: Date and Tweet. In our model, Dataset 1 was used for our supervised learning approach where we split the dataset into 80% training and 20% testing. The unlabeled Dataset 2 was used to experiment with an unsupervised approach for SVM, where the goal was to label tweets as positive, negative, and neutral. These datasets consisted of hashtags, emojis, hyperlinks, mentions, among other factors and these properties made the data challenging as it required significant cleaning and preprocessing in order for the information to be used in our model.


