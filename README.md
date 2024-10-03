# TweetSentimentAnalysis
-This is my personal tweet sentiment analysis project, a small draft for my fyp(final year project).
-I used Google Collab and downloaded Sentiment140 dataset with 1.6 million tweets from 'Kaggle'.
a brief description of the libraries and models that i have used in this project: -
* NumPy: Used for efficient numerical computations, especially when handling arrays and matrices.
* Pandas: Used for data manipulation and analysis, including data cleaning and preprocessing.
* re (Regular Expressions): Utilized for pattern matching and searching through text data, helping with data cleaning (removing unwanted characters or words).
  
*** nltk (Natural Language Toolkit):
* Stopwords: Helps remove common words (like 'and', 'the') that do not add value to the sentiment analysis.
* PorterStemmer: Used for stemming, which reduces words to their root form (e.g., "playing" becomes "play"), making the data more uniform.
* TfidfVectorizer: Converts text data into numerical format by assigning importance to words based on their frequency across documents, enabling the model to process text data.
  
* sklearn.model_selection.train_test_split: Splits the dataset into training and testing sets to evaluate model performance.
* Logistic Regression: A classification algorithm used for predicting sentiment (positive, negative, or neutral) based on the tweet data.
* sklearn.metrics.accuracy_score: Calculates the accuracy of the model's predictions by comparing them with the true labels.
