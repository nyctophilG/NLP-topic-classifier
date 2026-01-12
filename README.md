# Topic Classification (NLP Course CS401)
Overview

This repository contains the source code and documentation for the first major project of the semester: a Topic Classifier. The objective is to categorize text documents into predefined topics using a dataset sourced from Kaggle (e.g., AG News or 20 Newsgroups). This project explores the end-to-end NLP pipeline, from data ingestion and cleaning to model evaluation, as outlined in our course curriculum.

Dataset

We are using the https://www.kaggle.com/datasets/baraamelhem/topic-classification-dataset dataset.

    Download the dataset from Kaggle.
    
Key Dependencies:

    pandas & numpy: Data manipulation.

    scikit-learn: Model implementation (Naive Bayes, SVM) and evaluation metrics.

    nltk / spacy: Text preprocessing (tokenization, stop-word removal).

    matplotlib / seaborn: Visualization of confusion matrices.

Usage
1. Preprocessing

Run the preprocessing script to clean text and generate TF-IDF vectors

2. Training

Train the classifier (default: Multinomial Naive Bayes) and save the model

3. Evaluation

Generate the classification report and confusion matrix on the test set

Methodology

Following the lecture on probabilistic modeling, we implemented a baseline Multinomial Naive Bayes classifier. We are currently experimenting with Support Vector Machines (SVM) to compare performance. Future iterations may involve fine-tuning a transformer model (BERT) if computational resources allow.
