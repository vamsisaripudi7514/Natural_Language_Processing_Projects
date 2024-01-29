This project showcases the classfication of movie reviews into postive or negative.
The Term frequency Inverse document frequency vectorizer is used for feature extraction from the list of reviews avaialble.
A LinearSVC model is used for training and classification.
A pipeline containing TfidfVectorizer--->LinearSVC is created for easy implementation.

For data preprocessing null value rows are dropped and the dataset has no empty entries in the form of strings with spaces which is checked in the code.

Overall the model has achieved an accuracy_score of 92.8%
