# IMDBSentimentAnalysis
# 🎬 IMDB Movie Review Sentiment Analysis

A machine learning project that predicts whether a movie review is **positive** or **negative** using Natural Language Processing (NLP) techniques.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Iliofotos/IMDB-Sentiment-Analysis/blob/main/IMDB_Sentiment_Analysis.ipynb)

## Overview

This project uses the IMDB dataset (50,000 movie reviews) to train a Multinomial Naive Bayes classifier. The text is converted to numerical features using TF-IDF vectorization.

## Results

| Metric | Score |
|--------|-------|
| Accuracy | 85.44% |
| Balanced Accuracy | 85.44% |
| AUC | 0.93 |

## Approach

1. **Data Loading** - 50k reviews, balanced dataset (25k positive, 25k negative)
2. **Preprocessing** - TF-IDF vectorization with English stop words removed
3. **Model Training** - Multinomial Naive Bayes classifier
4. **Evaluation** - Accuracy, confusion matrix, ROC-AUC curve

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Quick Start

No setup required! Click the "Open in Colab" button above and run all cells.

Or run locally:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## Sample Predictions
```
Review: "This movie was absolutely amazing! Best film I've seen..."
Prediction: positive
Confidence: 92.3%

Review: "Terrible movie. Boring plot, bad acting..."
Prediction: negative
Confidence: 89.1%
```

## Future Improvements

- Try Logistic Regression or SVM for comparison
- Add bigrams (ngram_range=(1,2))
- Experiment with word embeddings (Word2Vec)

## Author

Iliofotos Iliofotou - [GitHub](https://github.com/Iliofotos) | [LinkedIn](https://linkedin.com/in/iliofotos-iliofotou-26244a155)
