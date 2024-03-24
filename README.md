# Sentiment Classifier 💬

This project focuses on classifying fake data from Twitter (tweets). It aims to determine whether a tweet is positive or negative by analyzing the presence of positive and negative words and calculating the net score. The net score indicates the overall sentiment of the tweet.



# Project Description 📝
    
  The project utilizes fake Twitter data stored in a CSV file named "project_twitter_data.csv", which includes the tweet text, the number of retweets, and the number of replies.
  
  Positive and negative sentiment words are listed in separate files named "positive_words.txt" and "negative_words.txt".

# Implementation Details 🛠️

1- Strip Punctuation Function: This function removes punctuation from the tweet text using a string.

2- get_neg && get_pos: It  determines the number of positive and negative words in the text

3- Resulting Data CSV: The project generates a CSV file named "resulting_data.csv", containing columns for the number of retweets, number of replies, positive score (indicating the presence of happy words), negative score (indicating the presence of angry words), and net score (overall sentiment) for each tweet.

4- Visualization: Additionally, the project produces a graph showing the relationship between the net score and the number of retweets.




# Conclusion 📊

This sentiment classifier provides insights into the sentiment of Twitter tweets, facilitating the identification of positive and negative sentiments within the data. The visualization enhances understanding by illustrating the correlation between sentiment and tweet engagement (retweets).




