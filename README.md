# sentiment-classifier
This project is for classifying fake data from Twitter (tweets). It is used to classify the tweet as positive or negative by calculating the count of negative words and positive words and finding the net score. Based on this, it calculates whether the sentence tends to be positive or not.

For a specific description of the project >>>

The project takes A fake Twitter date from a CSV file named project_twitter_data.csv which has the text of a tweet, the number of retweets, and the number of replies to that tweet.

Some words express positive and negative sentiments in the files positive_words.txt and negative_words.txt.


The Project is to build a sentiment classifier, which will detect how positive or negative each tweet is. and will create a CSV file, which contains columns for the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score for each tweet (difference of Positive and Negative Score ),

At first in the strip_punctuation Function, I pass String to remove punctuation from the text then get the number of positive/negative words in the text from the get_pos /get_neg function


Then create a CSV file called resulting_data.csv, which contains the number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score (how positive or negative the text is overall if>0 it positive if <0 negative ) for each tweet.

Then produce a graph of the Net Score vs the Number of Retweets
