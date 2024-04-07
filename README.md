# Sentiment Analysis with Web Scraped News Data

This project is aimed at conducting sentiment analysis on news articles scraped from the internet using Python. The sentiment analysis is performed using VADER (Valence Aware Dictionary and sEntiment Reasoner), which is a lexicon and rule-based sentiment analysis tool specifically designed for analyzing sentiments in text.

## Overview

* The notebook starts with installing necessary libraries and importing required modules.
* It then proceeds with web scraping news articles from different categories (technology, politics, world, sports) using BeautifulSoup and requests library.
* Textual data preprocessing is performed, which includes tasks like converting text to lowercase, removing HTML tags, expanding contractions, removing special characters, and removing stopwords using NLTK.
* Sentiment analysis is conducted on the preprocessed news articles using VADER, and the sentiment scores (compound score) are appended to the DataFrame.
* Finally, the DataFrame containing the news data along with sentiment scores is displayed.

## Getting Started 

* Open the command line or terminal. Clone this repository :

```
git clone https://github.com/NilBee/Sentiment-Analysis-of-Inshorts.git
```

* Install dependencies:

```
pip install -r requirements.txt
```

* To open with VSCode

```
code .
```

* To open with Jupyter notebook

```
jupyter-notebook
```


## Note
* This project is provided as a demonstration of sentiment analysis on textual data using Python.
* Make sure to abide by the terms of service of the websites you are scraping data from.
* The code provided is for educational purposes and can be modified according to specific use cases or requirements.