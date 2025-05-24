# Emotion Classifier using SVM

This project is a tweet-based emotion classification system using Support Vector Machines (SVM). It includes text preprocessing, multi-kernel SVM training, detailed evaluation, emotion monitoring thresholds, and alerting logic (email/Discord-ready).

## 📁 Dataset

The dataset must be a CSV file named `emotions.csv`, containing the following columns:

- `text`: Tweet content
- `label`: Integer (0–5) representing emotion class

| Label | Emotion   |
|-------|-----------|
| 0     | Sadness   |
| 1     | Joy       |
| 2     | Love      |
| 3     | Anger     |
| 4     | Fear      |
| 5     | Surprise  |

## 🧠 Features

- Text preprocessing with NLTK:
  - Lowercasing
  - Tokenization
  - Punctuation and stopword removal
  - Stemming
- TF-IDF feature extraction
- Multi-kernel SVM training:
  - Linear, RBF, Polynomial, Sigmoid
- Model evaluation:
  - Accuracy
  - Classification report
  - Confusion matrix
- Emotion distribution analysis
- Optional:
  - Email/Discord alerting based on emotion thresholds
  - PCA/t-SNE visualization
  - KMeans clustering and topic modeling (LDA)
