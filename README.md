# Customer-Sentiment-Analysis-for-British-Airways
Data Science Virtual Internship program by British Airways through Forage

## Project Overview

This project involves scraping customer feedback data from Skytrax, specifically focusing on British Airways airline reviews, and performing sentiment analysis to derive meaningful insights.

## Data Collection

Web scraping is performed using Python and BeautifulSoup from:
https://www.airlinequality.com/airline-reviews/british-airways

## Methodology

The analysis follows a rule-based (lexicon-based) approach for sentiment analysis without utilizing machine learning models.

### Data Preprocessing Steps:

- Text cleaning
- Tokenization
- POS tagging enrichment
- Stopwords removal
- Word stemming

### Sentiment Analysis

Using VADER (Valence Aware Dictionary and Sentiment Reasoner) for sentiment analysis, which provides both polarity and intensity of emotions in the reviews.

### Visualization

Word Cloud visualization will be implemented to display frequently occurring keywords and themes from the reviews.


## Dependencies

```
beautifulsoup4
pandas
nltk
vaderSentiment
wordcloud
matplotlib
```