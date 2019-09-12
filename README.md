# Open datasets for sentiment analysis based on tweets in English/Spanish/French/German/Italian

Most open datasets for text classification are quite small and we noticed that few, if any, are available for languages other than English. Therefore we want to make available to everyone this datasets for sentiment analysis.

We provides files with lists of tweets and their sentiments in:
* English tweets dataset => 6.3 millions tweets available.
* Spanish tweets dataset => 1.2m tweets.
*French tweets dataset => 250 000 tweets
* Italian tweets dataset => 425 000 tweets
* German tweets dataset => 210 000 tweets

The sentiment was generated thanks to AWS Comprehend API. For Spanish and French, tweets were first translated to English using Google Translate, and then analyzed with AWS Comprehend. 
Sentiment is classified to either positive, negative, neutral, or mixed.