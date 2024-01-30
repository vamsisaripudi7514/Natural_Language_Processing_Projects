This project showcases the classfication of movie reviews into postive or negative using Valence Aware Dictionary for Sentiment Reasoning (VADER).

The process begins with cleaning the data by removing null fields and fields with empty string values.

SentimentIntensityAnalyser module is used to calculate the polarity scores and are used to give out how VADER classifies the movie review according through sentiment intensity analysis.

The generated labels are compared with actual labels in the dataset to obtain the accuracy of predictions.

On the whole VADER achieved an accuracy of 63.67%
