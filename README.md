# NLP Project - Topic Modeling on Hotel Reviews

## Goal

There are countless reviews out there, but what are people really interested in? What are the keywords that the customers most look at before they make an online booking?
What keyword should hotel management businesses focus on so it can grab customer's attention? 
This project buils an unsupervised NLP model - Topic Modeling that helps hotels know what specific words they would have to focus on and improve in that specific area to better
target customers that are booking online. The data used for this project came from [Kaggle](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe). The data from 
Kaggle was originally scrapped from [Booking.com](https://www.booking.com/index.en-gb.html?label=gen173nr-1BCAEoggI46AdIM1gEaJMCiAEBmAEJuAEZyAEM2AEB6AEBiAIBqAIDuAKBytSGBsACAdICJDE2MTc1YTdiLTZjZTEtNGM3Yy05Yjk4LWJhYzlmNjY3MGY1M9gCBeACAQ;sid=59a1e940286b261e34afb110a622a0a9;keep_landing=1&sb_price_type=total&)
The dataset consists of 515,000 customer reviews consisting of 1,400+ hotels across Europe.

## Work/Presentation
1. [Initial WordCloud of Corpus](https://github.com/munwonjj/NLP_Project/blob/main/mvp.md)
2. [Topic Model Visualization with pyLDAvis](https://github.com/munwonjj/NLP_Project/blob/main/pyLDavis%20visualization.PNG)
3. [Final Presentation Slides](https://github.com/munwonjj/NLP_Project/blob/main/NLP%20Project%20%20%20Hotel%20Review%20Analysis.pdf)

## Tools

Libraries
* Numpy + Pandas
* NLTK, TFIDF, Tokenization, Removing stopwords
* Sklearn, CountVectorizer to create sparse matrix
* pyLDAvis for visualization

Topic Modeling
* NMF, LDA
