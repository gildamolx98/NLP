# Formative Assessment - Natural Language processing 

*Loading and Preprocessing*


- Loaded the dataset from the provided url.
- Preprocessed the text data by:
    - Removing URLs, usernames, and special characters.
    - Converting text to lowercase.
    - Tokenizing text into words.
    - Removing stopwords.


*Feature Extraction*


- Implemented feature extraction using both CounterVectorise and TfidfVectorizer.
- Transformed text data into numerical features using both Bag of Words and TF-IDF method.


*Model Development*


- Trained two machine learning models:
    - Naive Bayes (MultinomialNB).
    - Support Vector Machine (SVC).


*Model Comparison*


- Evaluated each model using accuracy, F1-score, classification report, and confusion matrix.
- Compared model performance to determine the best model for emotion classification
