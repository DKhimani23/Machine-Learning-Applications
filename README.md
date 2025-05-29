# Sentiment Analysis on IMDb Reviews – NLP Project

This repository showcases an NLP project that classifies IMDb movie reviews into positive or negative sentiment using both classical and deep learning models.

## Project Goals
- Compare ML models (Naïve Bayes, SVM, Logistic Regression, etc.)
- Fine-tune a BERT model on IMDb data
- Explore ensemble models (e.g., BERT + SVM)
- Extract themes using topic modelling (NMF, BERTopic)

## Techniques Used
- TF-IDF and word embeddings
- Model evaluation: precision, recall, F1-score, AUC
- Transformer fine-tuning
- Topic modelling and coherence analysis

## Files Included
- `Sentiment Analysis - Natural Language Processing.pdf` – full report
- `Natural Language Processing.ipynb` – code (classification + topic modelling)
- `Sentiment Analysis on IMDB reviews - ratings.pdf` – ratings and supplementary visuals

## Key Insights
- Best performance: **SVM with 86.6% accuracy**
- BERT models enhanced when combined with Logistic Regression (76.7%)
- Topic modelling: **NMF** showed strongest coherence score (0.553)

## Tools
Python · Scikit-learn · BERT · BERTopic · Matplotlib · Seaborn

---
