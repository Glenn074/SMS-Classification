# SMS-Classification
This project is a machine learning-based classification system designed to detect spam messages from SMS text data. It uses natural language processing (NLP) techniques to transform raw text into numerical features, followed by a classification model to distinguish between spam and ham (not spam) messages.

Dataset--
The project uses the SMS Spam Collection Dataset, which contains 5,572 English messages labeled as either:
ham – legitimate (non-spam) messages
spam – unsolicited messages

Model & Techniques--
Data Preprocessing:
Lowercasing
Removing stopwords and punctuation
Lemmatization

Feature Extraction:
TF-IDF Vectorization

Model Used:
Naive Bayes Classifier

Evaluation Metrics:
Accuracy
Precision, Recall, F1-Score
Confusion Matrix

Results--
The model achieves a high accuracy in distinguishing spam messages, demonstrating the effectiveness of combining NLP preprocessing with a Naive Bayes classifier.
