# dsi-project3
DSI Project 3 - Web API &amp; Classification

# Problem Statement
For this project, we will be using Reddit's API to collect posts from two subreddits and then use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem. Correct classification of posts in the forum is crucial as it enables users to be able to find the right information in the right place.

# Executive Summary
In this text classification project, we will attempt to classify posts from two subreddit forums: MachineLearning and ArtificialIntelligence. In view of the close similarity between thee two topics, we will explore using three different classification models (LogisticRegression, Naive Bayes and GradientBoostingClassifier) and evaluate its performance based on the accuracy score. The following data science process will be carried out.

- Define problem statement
- Gather Data
- Explore Data
- Data Cleaning & Pre-processing
- Create Model
- Evaluate Model
- Answer Problem
- Conclusion and Recommendation

# Conclusion/Recommendation
In this project, the data collected from two reddit subforums: artificial intelligence and machine learning were cleaned, pre-processed and modelled by LogisticRegression and Naive Bayes using both the techniques of CountVectorizer and TF-IDF for converting text to feature matrix.

The performance was evaluated based on the accuracy score of the models obtained for both training and testing data. The best accuracy score was obtained from the Naive Bayes model using Countvectorizer, with a training score of 90% and testing score of 81%.

Data analysis on all the posts that were mis-classified (for both labels) were carried out to understand how the model can be improved. It was observed that majority of the mis-classified posts were tagged with the wrong labels at the source (e.g posts with machine learning key words were posted in the aritificial intelligence subforums).

In order to improve the model's performance, more data can be collected and use to train the model. Alternatively, this model can also be used to re-classify the wrongly posted post to the correct subreddit forum. This will improve user experience so that users are able to find the right information in the right subforums.
