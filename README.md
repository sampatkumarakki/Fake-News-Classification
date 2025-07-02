# Fake News Detection Using Word2Vec and Supervised Learning

## Overview

This project focuses on building a **Semantic Classification model** to detect fake news articles. Unlike traditional models that rely only on surface-level features (like word counts), this model aims to understand the **meaning** of the text using **Word2Vec embeddings**, enabling more intelligent and accurate classification.

---

## Objective

The goal of this project is to develop a semantic classification model that can distinguish between true and fake news articles by learning the underlying patterns in language and writing style. With the growing flood of digital content, especially on social media and news platforms, fake news has become a major concern, affecting public opinion, safety, and trust.

This model aims to:
- Automatically classify news articles as **true** or **fake**
- Capture **semantic meaning** using Word2Vec embeddings
- Train **supervised learning models** that go beyond syntax to understand context
- Support broader efforts to reduce misinformation and support fact-checking

---

## Approach

1. **Data Preprocessing**
   - Clean and normalize the text (punctuation removal, lowercasing, etc.)
   - Tokenize the articles and prepare them for embedding

2. **Feature Engineering**
   - Use pre-trained or custom-trained **Word2Vec** embeddings
   - Represent each article as an average of its word vectors

3. **Modeling**
   - Train supervised models (e.g., Logistic Regression, SVM, Random Forest)
   - Use labeled datasets of fake and true news for training and testing

4. **Evaluation**
   - Evaluate model performance using accuracy, precision, recall, and F1-score
   - Use cross-validation to check generalization
