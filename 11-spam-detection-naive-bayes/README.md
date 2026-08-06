# Spam Detection using NLP and Naive Bayes

A text classification project that builds a full NLP pipeline from scratch, cleaning raw text, converting it into numbers, and training a model to detect spam messages. Also explores cosine similarity to measure how alike different messages are.

## What This Covers

- Building a custom text cleaning function (lowercasing, removing punctuation/numbers, removing stopwords, stemming with `PorterStemmer`)
- Applying the cleaning function across a full dataset using `.apply()`
- Converting cleaned text into numeric features using `TfidfVectorizer`
- Splitting data into train and test sets
- Training a `MultinomialNB` (Naive Bayes) model for spam classification
- Evaluating performance using `classification_report`
- Measuring text similarity between messages using `cosine_similarity`

## Key Learning

Practiced the full NLP pipeline: **Clean → Vectorize → Model**. Also learned firsthand how small, imbalanced datasets can produce unstable classification results, and why real world text classifiers need much larger datasets to perform reliably.

## Tools & Libraries Used

- Python
- Pandas
- NLTK (`stopwords`, `PorterStemmer`)
- Scikit-learn (`TfidfVectorizer`, `MultinomialNB`, `train_test_split`, `classification_report`, `cosine_similarity`)

## Dataset

A small custom-built dataset of 30 labeled text messages (spam vs not spam), created manually for practice purposes.
