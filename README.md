# Tales from the Crypto

## Background

In this assignment, natural language processing was used to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. Other NLP techniques were applied to better understand the factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

### Sentiment Analysis

[News Api](https://newsapi.org/) was used to pull the latest news articles for Bitcoin and Ethereum. Dataframes of sentiment scores were created for each coin.

Descriptive Statistics were used to answer the following questions:

1. Which coin had the highest mean positive score?

    Bitcoin had the highest mean positive score of `0.089350` vs Ethereum `0.072647`.

2. Which coin had the highest negative score?
   
   Ethereum had the highest negative score at `0.189000` in comparison to Bitcoin `0.071000`.

3. Which coin had the highest positive score?

    Ethereum had the highest positive score `0.209000` and Bitcoin had a score of `0.198000`.

### Natural Language Processing 

In this section, NLTK and Python were used to tokenize text, find n-gram counts, and create word clouds to summarize the news for both coins. 

#### Top 10 words for Bitcoin:

![Top 10 Bitcoin](Images/topten_bitcoin.JPG)

#### Top 10 words for Ethereum:

![Top 10 Ethereum](Images/topten_ethereum.JPG)

#### Word Clouds for Bitcoin and Ethereum:

![Bitcoin Word Cloud](Images/bitcoin_wc.JPG)

![Ethereum Word Cloud](Images/ethereum_wc.JPG)

### Named Entity Recognition

Named entity recognition(NER) models were created for both coins and tags were visualized using SpaCy.

#### Sample Bitcoin NER:

![Bitcoin NER](Images/bitcoin_ner.JPG)

#### Sample Ethereum NER:

![Ethereum NER](Images/ethereum_ner.JPG)