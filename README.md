# Twitter-Sentiment-Analysis

This project applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to perform sentiment analysis on Twitter data. The model classifies tweets as **positive**, **negative**, or **neutral**, helping to understand public sentiment about a topic in real-time.

## 🔍 Overview

The notebook walks through the complete process of:
- Preprocessing raw tweet text (cleaning, tokenization, stop word removal, etc.)
- Feature extraction using TF-IDF vectorization
- Training and evaluating several ML models (e.g., Logistic Regression, Naive Bayes)
- Displaying performance using accuracy, confusion matrix, and classification report

## 📊 Dataset

This project uses a dataset of tweets labeled with sentiments (positive, negative, neutral). If you are using an external dataset, ensure it contains at least the following columns:
- `text`: The tweet content
- `target`: Sentiment label (e.g., 0 = negative, 2 = neutral, 4 = positive)

> Note: Due to Twitter API changes, scraping live tweets is not part of this notebook.

## 🛠️ Features

- Text preprocessing pipeline:
  - Removing links, special characters, hashtags, mentions
  - Lowercasing, lemmatization
- Sentiment classification using:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Support Vector Machines (optional extension)
- Evaluation with:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-Score

## 🚀 How to Run

You can run this notebook directly in **Google Colab**:

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `Twitter_Sentiment_Analysis.ipynb` notebook
3. Run the notebook cells in order to preprocess data, train models, and evaluate performance

## 📈 Sample Output

- Word clouds of positive and negative tweets
- Bar plots of sentiment distribution
- Confusion matrix and classification metrics for model performance

## ✅ Future Improvements

- Use of pre-trained embeddings like Word2Vec, GloVe, or BERT
- Integration with Twitter API for live tweet analysis
- Deployment via a Flask/Django web app or Streamlit

## 🧠 Author

**Angelina Mande**  
