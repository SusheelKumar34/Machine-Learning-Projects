# SMS Spam Detection System

This project involves the implementation of an SMS spam detection system. The system is designed to classify SMS messages as either "spam" or "ham" (not spam) using various machine learning techniques.

## Processes and Functions

The project can be broken down into several key processes and functions:

- **Data Preprocessing and Cleaning**: This is the first step in any machine learning project. It involves cleaning the data by removing irrelevant information, handling missing data, and converting text data into a format that can be used by a machine learning model.

- **Bag-of-Words and TF-IDF Implementation**: These are techniques used to convert text data into numerical vectors. The Bag-of-Words model represents each text as a bag (multiset) of its words, disregarding grammar and word order but keeping multiplicity. On the other hand, TF-IDF (Term Frequency-Inverse Document Frequency) is a statistical measure that evaluates how relevant a word is to a document in a collection of documents. Implementing these from scratch in Python provides a deeper understanding of how they work.

- **Model Creation**: This involves creating a model using Gaussian, Multinomial, and Bernoulli Naive Bayes classifiers. These are different types of Naive Bayes classifiers which are based on applying Bayes' theorem with strong (naive) independence assumptions between the features.

## Learnings from this Project

This project provides valuable experience in:

- **Natural Language Processing (NLP)**: The project involves working with text data, providing hands-on experience with NLP techniques such as text cleaning and text representation.

- **Machine Learning**: Implementing and comparing different types of Naive Bayes classifiers provides a practical understanding of these machine learning algorithms.

- **Python Programming**: Implementing Bag-of-Words and TF-IDF from scratch helps in improving Python programming skills, particularly in relation to data manipulation and analysis.

- **Model Evaluation**: The project involves evaluating the performance of the models, providing experience with concepts such as precision, recall, and F1-score.
