Built a supervised classification model for estimating the veracity of a news story using supervised learning

Preprocessed data set by handling the missing values, encoded the categorical data into integer data, and feature scaling using 
classes from the Scikit-learn library.

Removed punctuation marks and stopwards from the text data and stemming of each words to make the tect data ready for feature engineering using NLTK Library

Initialized TF-IDF vectorizer to convert the text data by counting the word frequency and convert the text data into a matrix of TF-IDF features

Initialized a Passive Aggressive Classifier algorithm and MultinomialNb classifier to train the classification model on the TF-IDF matrix which is a 2-d array which shows the importance of each of the words in the document.

Comapared the accuracy of both the algorithms on the dataset by calculating the accuracy score and Cross-Validation metrics.
