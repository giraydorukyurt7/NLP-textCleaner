# textCleaner Function

## Overview
The purpose of this function is to speed up the text processing process. 
It is designed to clean and preprocess text data for further analysis, 
ensuring that your data is in optimal shape for machine learning or natural language processing (NLP) tasks.

## Features
- Removes HTML elements from text using BeautifulSoup.
- Transforms to lower case.
- Removes punctions from text.
- Removes numbers   from text.
- Removes stopwords from text.
- Removes rarewords from text.
- Lemmatizes words for better text normalization.
- Removes extra spaces from text.

##IMPORTANT: Download these packages before use
```bash
nltk.download('stopwords')     # --> Text Preprocessing
```
```bash
nltk.download('wordnet')       # --> Text Preprocessing
```

## Note: 
### If you want to use this code the dataframe shouldn't have null values.
Example for handling null values:
```bash
df = df.dropna(subset="Review")
```

## Installation and Requirements
Make sure you have the following Python packages installed:
- `pandas`
- `BeautifulSoup4`
- `nltk`
- `textblob`

You can install them using:
```bash
!pip install pandas beautifulsoup4 nltk textblob
```
