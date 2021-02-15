# Email Spam Detector using NLP

Used a dataset that already had some emails that were classified as spam or not spam. Then clean up the data and removed punctuation and common stopword. After than, I used some sckit-learn's feature extraction class to apply Count Vectorizer and then Tfidftransform. I then applied sklearn's MultinomialNB classifier on that data. I used that trained model to predict if an email was spam or not on a test data and used sklearn's metrics to see how well my model performed.
