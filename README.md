# Sentiment Analysis on Snappfood Reviews

## Overview
This project focuses on sentiment analysis of user reviews from [Snappfood](https://snappfood.ir), an online food delivery platform. The dataset comprises 56,700 reviews labeled as positive or negative based on user sentiment.

## Dataset Description
The dataset contains a collection of reviews gathered from Snappfood users. Each review is labeled as either positive or negative to indicate user sentiment towards their experience with the platform's services.

Total Reviews: 56,700
Labels: Positive, Negative

## Project Goal
The primary objective of this project is to develop a machine learning model that accurately predicts the sentiment (positive or negative) of user reviews. This model can be utilized to automatically analyze and classify incoming reviews, providing valuable insights into customer satisfaction and identifying areas for improvement.

## Methodology
### Data Preprocessing: 
Text preprocessing techniques such as tokenization, stop word removal, and stemming were applied to clean and normalize the text data.

### Feature Engineering: 
The cleaned text data was converted into numerical feature vectors using techniques to prepare it for machine learning algorithms.

### Model Selection and Training: 
Several machine learning algorithms were explored and evaluated, including Random Forest, Naive Bayes, and SVM to determine the best-performing model for sentiment classification.

### Model Evaluation: 
The models were evaluated based on metrics such as accuracy, precision and recall on both training and test datasets to assess their performance.

![Train](https://github.com/MohammadMardi/Sentiment-Analysis/blob/main/TrainAccuracy.png)

![Test](https://github.com/MohammadMardi/Sentiment-Analysis/blob/main/TestAccuracy.png)

![Precision](https://github.com/MohammadMardi/Sentiment-Analysis/blob/main/Precision.png)

![Recall](https://github.com/MohammadMardi/Sentiment-Analysis/blob/main/Recall.png)
