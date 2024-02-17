# Sentiment Analysis Project

## Overview
This project performs sentiment analysis on news headlines scraped from CNBC and Google News RSS feeds. It analyzes the sentiment of headlines related to "green hydrogen" and provides insights into the overall sentiment trends.

## Features
- Scrapes news headlines from CNBC and Google News RSS feeds.
- Utilizes the Hugging Face Transformers library for sentiment analysis.
- Generates a DataFrame containing headline text, sentiment label, and sentiment score.
- Visualizes the week-wise trend of the average sentiment score.
- Creates a word cloud highlighting organization names mentioned in the headlines.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/sentiment-analysis-project.git
## Install the required Python packages:
   pip install pandas requests beautifulsoup4 transformers wordcloud spacy
   python -m spacy download en_core_web_sm

## Usage
   1. Run the main script main.py to perform sentiment analysis and generate visualizations:
    python main.py
  2.View the resulting DataFrame and visualizations.

## Dependencies
pandas
requests
beautifulsoup4
transformers
wordcloud
spacy

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
