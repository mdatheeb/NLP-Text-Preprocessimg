# NLP Text Preprocessing Pipeline

This repository provides a robust Python script for cleaning and preparing raw text data for NLP models. It is specifically designed to handle social media data (like tweets) by removing handles, URLs, and emojis.

## Features
* **Data Cleaning:** Removes HTML tags, URLs, and special characters.
* **Emoji Handling:** Converts emojis into text descriptors.
* **NLTK Integration:** Performs tokenization, stemming (Porter), and lemmatization (WordNet).
* **Batch Processing:** Uses Pandas to process entire datasets efficiently.

## Installation
Ensure you have Python installed, then run:
```bash
pip install nltk pandas emoji
