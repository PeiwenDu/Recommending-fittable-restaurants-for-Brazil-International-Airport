# Recommending-fittable-restaurants-for-Brazil-International-Airport

# The project description
The project is aimed at enhancing customer satisfaction and Brazil Rio Galeao International airport's profitability. We defined the existed restaurants' ratings in the airport, and used those restaurants to train supervised machine learning models, finally used the best model to suggest other restaurants in Brazil which would be suitable to this airport.

# My work
Calculated restaurant’s customer traffic by Kiana footprint dataset and defined the restaurants’ ratings.
Rated the restaurants which couldn’t get customer traffic from Kiana by creating a KNN classifier.
Extracted the features from cleaned review text using TF-IDF and vectorized features by Word2vev models which were trained in a 6.33G Yelp review dataset. Trained the word vectors with different dimensions from 50-300 to get better models.
Built SVM, Logistics Regression, CNN using restaurants’ features and ratings. Logistics Regression reached 87.5% high accuracy.
Distinguished other good restaurants in Brazil based on the LR model and visualized it.

# Code
https://colab.research.google.com/drive/1F2gaRY8Yu-ldbOUdIgJhnunrd0zuwqFD?usp=sharing
