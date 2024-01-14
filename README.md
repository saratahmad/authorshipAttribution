# Authorship Attribution
Project Overview
In this project, we use the data generated using six Twitter users’ scraped tweets to maketraining and test datasets. Three machine learning models are used to train and test the data for Authorship Attribution

Feature Preparation:
‍Data is split in an appropriate split ratio, and a collective vocabulary and a correspondingbag of word features are made. In addition to this, BERT Sentence Embeddings are used toget the features. The advantage of using this over features based on pure counts is theinclusion of context and semantic information, which means that the features code richerinformation and can therefore lead to models performing better given that they provide ahigher quality input.

KNN:
‍1. Scikit Learn’s KNN model is used to get predictions for authorship attribution.
2. 5-fold cross-validation is performed
3. Scikit-learn functions are used to report the accuracy, classification report includingmacro-average (precision, recall, and F1), and confusion_matrix function.

NN:
‍1. Scikit Learn’s NN model is used to get predictions for authorship attribution.
2. 5-fold cross-validation is performed3. Scikit-learn functions are used to report the accuracy, classification report includingmacro-average (precision, recall, and F1), and confusion_matrix function.

Ensemble Methods:
1. Used Random forests as Ensemble methods for training and prediction.
2. Scikit-learn functions are used to report the accuracy, classification report including macro-average (precision, recall, and F1), and confusion_matrix function.
