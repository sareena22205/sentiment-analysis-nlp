# Sentiment Analysis on Product Reviews using NLP

An NLP pipeline that classifies customer product reviews into positive, negative, and neutral sentiment.

## Overview
Built an end-to-end NLP pipeline to process and classify over 15,000 customer product reviews, extracting sentiment trends to support product and customer service decisions.

## Tech Stack
- Python
- NLTK, TextBlob
- TensorFlow
- TF-IDF Vectorization

## Approach
1. **Text Preprocessing** — cleaned raw reviews (lowercasing, stopword removal, lemmatization) and tokenized text.
2. **Feature Extraction** — applied TF-IDF vectorization to convert text into numerical features.
3. **Model Training** — trained a classifier to predict sentiment (positive / negative / neutral) across the review set.
4. **Insight Extraction** — analyzed sentiment trends over time and by product category to surface actionable feedback.

## Results
- Classified **15,000+ reviews** with **91% accuracy**.
- Sentiment trend analysis surfaced recurring complaint themes, informing product improvement recommendations.

## Project Structure
```
sentiment-analysis-nlp/
├── data/                    # Raw and cleaned review data
├── notebooks/                # EDA and experimentation
├── src/
│   ├── preprocessing.py      # Tokenization, TF-IDF
│   ├── train.py               # Model training
│   └── analyze_trends.py     # Sentiment trend extraction
├── requirements.txt
└── README.md
```

## How to Run
```bash
pip install -r requirements.txt
python src/preprocessing.py
python src/train.py
python src/analyze_trends.py
```

## Author
Sareena Ashfaque Shaikh — [LinkedIn](https://linkedin.com/in/sareena-ashfaque-shaikh)
