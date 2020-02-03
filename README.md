# Title: NLP-with-Disaster-Tweets

#### Authors: Srikanth Babu Mandru

### Summary: 

This project mainly focuses on applying the machine learning and deep learning techniques for prediction of disaster from the tweet which is clear for human but not for computer as it will be mostly stated metaphorically. Thus, it is difficult to exactly predict whether a tweet is disaster or not. I have worked on this project with different ML models while preprocessing the data with various techniques. I am currently working on this and will update this repository as project progess.

**Dataset Source:**

Data is taken from kaggle and it is part of running competition in Kaggle.

https://www.kaggle.com/c/nlp-getting-started/data 

### Models and Approach:

Preprocessed the tweets text data with "tweet-preprocessor". 

Also, For deep learning techniques, I have used "Glove-6B-100d" embeddings for the tokens (words) representation in order to capture the essence of intuition of using the word in the tweet.

Most of ML models were implemented and ensembles methods were also tried with best performing models as the member classifiers.

Later, I have started using deep neural networks with various modifications and trying upon finding the best architecture for this problem along with changing the embeddings and preprocess steps.  

### Results:

Evaluated the models through F1-score (since the class distribution is not balanced). Till now, achieved the average validation F1-score around "0.73". I am working on to improve this further !!!!  

