# Tech News Topics: 2011-2020

**Description**

This project explored the subreddit Tech News using natural language processing and unsupervised learning. Used NLP and topic modeling techniques on ten year's worth of data to identify themes in technology news and changes over time. Preprocessed the text with NLTK to include bi-grams, keep only nouns, and add additional stop words. Ran topic modeling on the corpus using CountVectorizer, TF-IDF, NMF, and LDA. CountVectorizer with NMF topic modeling yielded easily labelable themes in technology. Sentiment analysis of the community comments was examined with the pre-trained models TextBlob and Vader. 


**Data Source**

* Subreddit r/technews [https://www.reddit.com/r/technews/](https://www.reddit.com/r/technews/)


**Tools**

* Reddit API
* Pushshift API
* MS Excel
* Python

Python packages:

* Pandas 
* Numpy
* Pickle
* PRAW
* PSAW
* Matplotlib
* Seaborn
* SciKit-Learn
* NLTK
* TextBlob
* VaderSentiment
