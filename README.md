## Support me on Medium
Become a member on Medium and support my work (affiliate link): https://medium.com/@charlesmalafosse/membership

# Open datasets for sentiment analysis 
based on tweets in English/Spanish/French/German/Italian

Most open datasets for text classification are quite small and we noticed that few, if any, are available for languages other than English. Therefore we want to make available to everyone this datasets for sentiment analysis.

We provides files with lists of tweets and their sentiments in:
* **English tweets dataset** => 6.3 millions tweets available.
  * betsentiment-EN-tweets-players	- 273Mo	- 1.9m lines
  * betsentiment-EN-tweets-teams	- 519Mo	- 3.5m lines
  * betsentiment-EN-tweets-worldcup	- 128Mo	- 943.2k lines
* **Spanish tweets dataset** => 1.2m tweets.
  * betsentiment-ES-tweets-teams	- 20Mo -	132.7k lines
  * betsentiment-ES-tweets-worldcup	- 136Mo -	1.1m lines
* **French tweets dataset** => 250 000 tweets
  * betsentiment-FR-tweets-teams	- 10Mo	- 62.9k lines
  * betsentiment-FR-tweets-worldcup -	27Mo	- 191.5k lines
* **Italian tweets dataset** => 425 000 tweets
  * betsentiment-IT-tweets-players	- 24Mo -	165.8k lines
  * betsentiment-IT-tweets-teams	- 38Mo	- 259.6k lines
* **German tweets dataset** => 210 000 tweets
  * betsentiment-DE-tweets-players	- 16Mo -	101.7k lines
  * betsentiment-DE-tweets-teams	- 16Mo -	109.0k lines


More on how to use them with my article on Medium:
https://towardsdatascience.com/fasttext-sentiment-analysis-for-tweets-a-straightforward-guide-9a8c070449a2

## About the data

Tweets were collected using the Twitter API between May and September 2018. The sentiment was generated thanks to AWS Comprehend API. For Spanish and French, tweets were first translated to English using Google Translate, and then analyzed with AWS Comprehend. 
Sentiment is classified to either positive, negative, neutral, or mixed.

Files are zipped and in csv format. Zip files larger than 25MB are split in smaller files using 7zip. One tweet per line and number of lines indicated above.

Data is provided free, as is, and without warranty under the MIT license.
