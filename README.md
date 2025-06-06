# NLP
Sentiment Analysis/ NLP University Project

# Arabic Emotion Detection using NLP,  Machine Learning and NNs

This is my first complete Natural Language Processing (NLP) project, where I built a full pipeline to detect emotions in Arabic tweets using both classical machine learning and deep learning techniques.

## Project Overview

- **Dataset**: [Emotional Tone Arabic Dataset](https://github.com/amrmalkhatib/Emotional-Tone)
- **Language**: Arabic
- **Goal**: Classify Arabic tweets into emotional categories (e.g., anger, joy, sadness)

## Techniques Used

### Preprocessing:
- Arabic text cleaning (punctuation, diacritics, stopwords)
- Tokenization and normalization

### Feature Representation:
- Bag-of-Words (BoW)
- TF-IDF
- Word2Vec (using pretrained **AraVec** embeddings)

### Models:
- **Classical ML**:
  - Naive Bayes (MultinomialNB)
  - Support Vector Machine (SVM with RBF kernel)
  - Decision Tree
  - Random Forest
  - AdaBoost
- **Deep Learning**:
  - Feed-Forward Neural Network (FNN)
  - LSTM (using tokenized sequences and embedding layers)
- **Tuning**: GridSearchCV for optimal parameters

## Evaluation

All models were evaluated using:
- Accuracy
- Precision (Macro/Weighted)
- Recall (Macro/Weighted)
- F1 Score (Macro/Weighted)

**Best performance:**
- **SVM with TF-IDF** for classical ML
- **LSTM with Word2Vec** for deep learning

## Challenges

- Handling Arabic morphological complexity
- Text normalization across different forms
- Model performance tuning

## Author

Made with ❤️ by [Raghad Al-Ta'amari]  
Student at The Hashemite University Data Science & AI
