# Open datasets for sentiment analysis 
based on tweets in English/Spanish/French/German/Italian

Most open datasets for text classification are quite small and we noticed that few, if any, are available for languages other than English. Therefore we want to make available to everyone this datasets for sentiment analysis.

We provides files with lists of tweets and their sentiments in:
* English tweets dataset => 6.3 millions tweets available.
* Spanish tweets dataset => 1.2m tweets.
  * betsentiment-ES-tweets-teams	20Mo	132.7k lines
  * betsentiment-ES-tweets-worldcup	136Mo	1.1m lines
* French tweets dataset => 250 000 tweets
* Italian tweets dataset => 425 000 tweets
* German tweets dataset => 210 000 tweets


More on how to use them with my article on Medium:
https://towardsdatascience.com/fasttext-sentiment-analysis-for-tweets-a-straightforward-guide-9a8c070449a2

## About the data

Tweets were collected using the Twitter API between May and September 2018. The sentiment was generated thanks to AWS Comprehend API. For Spanish and French, tweets were first translated to English using Google Translate, and then analyzed with AWS Comprehend. 
Sentiment is classified to either positive, negative, neutral, or mixed.

Files are zipped and in csv format. Zip files larger than 25MB are split in smaller files using 7zip. One tweet per line and number of lines indicated below in the download section.

Data is provided free, as is, and without warranty under the MIT license.
