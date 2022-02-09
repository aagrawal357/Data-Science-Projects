# Predicting popularity of a song and designing a music recommender system

1) Engineered an XGBoost Regression model to predict the popularity of a song on a scale of 1-100. The model was able to predict popularity with a mean absolute error (MAE) of 9 points and could help music producers and artists in foreseeing popularity of their songs. 
Highlights - 
 - Implemented K-means algorithm to cluster songs to see if songs with similar popularity would cluster together. They didn't.
  - Tried several algorithms such as linear regression, KNN regression, XGBoost regression, and 
Neural network and identified XGBoost as the best model, based on its superior performance on the validation dataset.
 - Additionally, tried a multi-class classification technique, using XGBoost classification, to categorize the popularity of a song, instead of predicting the exact value.
 
2) Designed a Spotify’s song radio like feature to recommend top 5 similar songs, using Principal Component Analysis (PCA) and the Nearest Neighbors algorithm.