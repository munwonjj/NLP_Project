# Analyzing Hotel Reviews Texts - Recommendation to Hotels based on Topic Modeling

NLP Project with visualizations using hotel data scraped from Bookings.com

## Abstract

Before making a reservation for your long awaited vacation, the first thing most people do before they book a hotel reservation is to look at differet reviews.
There are many different reviews out there and what are the most relevant or prevalent topics?
The goal of this project is to build an unsupervised NLP model(Topic Modeling) that helps hotels know what specific words they would have to focus on and improve
in that area to better target customers that are booking online.

## Data

The data used for this project came from [Kaggle](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe). The data from Kaggle was originally scraped from
[Booking.com](https://www.booking.com/index.en-gb.html?label=gen173nr-1BCAEoggI46AdIM1gEaJMCiAEBmAEJuAEZyAEM2AEB6AEBiAIBqAIDuAKBytSGBsACAdICJDE2MTc1YTdiLTZjZTEtNGM3Yy05Yjk4LWJhYzlmNjY3MGY1M9gCBeACAQ;sid=59a1e940286b261e34afb110a622a0a9;keep_landing=1&sb_price_type=total&)
The dataset consists of 515,00 customer reviews consiststing of 1400+ hotels across Europe.

## Design

Pre-Processing:
- Lower case, filter out default words for no reviews
- Use regex and string for more cleaning
- Use gensim for phrase detection
- Remove stopwords with NLTK + Tokenize, use Lemmatization and keep Nouns, Adjectives, Verbs, Adverbs

Topic Modeling:
- Choose LDA as final model to explore latent relationship in the corpus with Latent Dirichlet Allocation

Visualization:
- Present findings using pyLDAvis visualization to explain topic prevalence and similarity

## Algorithms/Tools

Libraries
* Numpy + Pandas
* NLTK, TFIDF, Tokenization, Removing stopwords
* Sklearn, CountVectorizer to create sparse matrix
* pyLDAvis for visualization 

Topic Modeling
* NMF, LDA

## Communication
1. WordCloud of Cleaned Corpus
![WordCloud](https://github.com/munwonjj/NLP_Project/blob/main/wordcloud.png)

2. pyLDAvis Visualization for Topic 1
![Visuals](https://github.com/munwonjj/NLP_Project/blob/main/pyLDavis%20visualization.PNG)
