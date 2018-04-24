# PositiveNews

Positive News is a look at major news organizations and their outlook from their public tweets.
The script reads the latest 100 tweets by five major news organizations nad uses the VADER Sentiment Analysis to put a value to how Positive, Negative, or Neutral the wording of the tweets rank. 
In the VADER Sentiment Analysis, words are analyized and ranked based on their posititive/neutral/negative outlook. Together, the score is compounded to give a ranking score between -1 to 1.
A score of 0 in VADER means the sentiment is completely neutral, while 1 is completly positive and -1 completly negative. A good way to think about it is taking the score and converting it to a percentage: A score of 1 would be 100% positive and probobly only contains words like happiness, rainbows, and love.

In order to run this script locally for yourself, you will need your own Twitter API keys to pull data.
Visit https://developer.twitter.com/ for more information.
