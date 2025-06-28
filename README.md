
# Sentiment Analysis with TextBlob and NLTK

This project performs sentiment analysis on textual data (e.g., tweets, reviews) using natural language processing (NLP) techniques. It classifies input text into Positive, Negative, or Neutral sentiments based on polarity scores.

## Features
- Text preprocessing (lowercasing, punctuation & URL removal, stopword filtering)
- Tokenization using NLTK
- Sentiment scoring using TextBlob
- Labeling sentiment as Positive, Negative, or Neutral
- Applied to both single sentences and batch datasets

## Technologies Used
- Python
- Google Colab
- NLTK
- TextBlob
- Pandas & Matplotlib (for data handling and visualization)

## Sample Input
```text
"I loved the food at that place! 😍 Best experience ever!!!"

## Sample Output

Sentiment: Positive
Polarity Score: 0.85
