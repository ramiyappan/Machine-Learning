# Sentiment Analysis

This project was part of assignments from the Data Mining course *(CS 584 - Spring '22)* at George Mason University.

## Files on the Repository


## Business Problem

Analyze sentiments of Amazon's baby product reviews by classifying them as positive or negative sentiments.

## Objectives

The objectives of this assignment are the following:
  - Handle text data *(product reviews)*
  - Use libraries to train and test Logistic Regression models on representations of the text data.

## Dataset

  - In test.dat you are only provided the reviews but no ground truth rating *(no target variable)*.

  - The training data also contains 18506 reviews *(in the file train_file.dat)*. Each row begins with the sentiment score followed by the text corresponding to the review.

  - format.dat shows an example file containing 18506 rows alternating with +1 and -1.

## Detailed Description:

A practical application in e-commerce applications is to infer sentiment *(or polarity)* from free form review text submitted for range of products.

Use a Logistic Regression classifier to predict the sentiment for 18506 reviews for baby products provided in the test file *(test.dat)*. 

Positive sentiment is represented by a review rating of +1 and Negative Sentiment is represented by a review rating of -1. 

You may choose any appropriate representation of the text data. We suggest experimenting with bag of words and ngram representations, with and without TF-IDF weighting.

Your test.dat should be similar to format.dat with the same number of rows i.e., 18506 but of course the sentiment score generated by your developed model.

