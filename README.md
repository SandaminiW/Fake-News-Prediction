# Fake-News-Prediction
 Fake News Prediction using Machine Learning with Python

# Project Overview
This project aims to build a machine learning model to distinguish between real and fake news. The dataset used is loaded into a pandas DataFrame, and missing values are analyzed. The project involves several key steps:

1. Data Preprocessing: Stop words are removed, and stemming is applied to clean the news text.
2. Feature Extraction: TF-IDF Vectorization is employed to transform text data into numerical features.
3. Modeling: A Logistic Regression model is trained on the preprocessed data to classify news as real or fake.
4. Model Evaluation: The accuracy of the model is assessed using common metrics like accuracy score, ensuring that the model's predictions are reliable.

# About the Dataset:

id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks whether the news article is real or fake:

1: Fake news
0: real News

# Dataset Used 
(kaggle Websit)

# Final Conclusion
The project successfully implements a fake news detection model using Logistic Regression. After preprocessing the data and transforming it into numerical vectors, the model is able to classify news with good accuracy. The use of TF-IDF vectorization helped in capturing important textual features, and the model performed well in identifying patterns in the data. Future improvements could include experimenting with other algorithms such as Random Forest or Neural Networks to enhance prediction accuracy.   
