# Fake_News_Detection
Using Machine Learning and NLP to segregate the unreliable and reliable news articles

## Thee Datasert
The data comes from Kaggle, you can download it here:
https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

There are two files, one for real news and one for fake news (both in English) with a total of 23481 "fake" tweets and 21417 "real" articles.

## The Anlysis
This project analyzes about 43k news articles and their titles, lemmatizes and cleans them and then uses them as features, which are then used in Logistic Regression, to classify them as reliable (0) or not reliable (1). It is able to achieve a test set accuracy of 98.76%.
