# Sentiment-Analysis-Projects

1. Amazon Fine Food Reviews:  

This dataset consists of reviews of fine foods from Amazon. It was collected over a period of 10 years and includes 
reviews up to October 2012. The dataset contains information about a product, the userid, the profile name for the name of the user and 
some information about the reviews that were posted by them. 

The helpfulness numerator is the number of users who found the review useful, the helpfulness deniminator happens to be the opposite. 
The score is the score that was given by the customer. A review contains a title/summary and the text/review.

I made use of Python to visualize wordclouds to understand which words seemed to stand out to most.

I also wanted to see if they seemed to express a positive or negative sentiment.

I made use of logistic regression to predict the sentiment of a review.

The results can be found in the "Kaggle - Amazon Fine Food Reviews-2.ipynb" notebook. 

2. Midnights Sentiment Analysis:

Created a Python list of urls for all the songs from the Midnights album 

Created a dataset that contains 3 columns using python's 'pandas' library : title, lyrics and sentiment score.

Scraped lyrics from the list of urls using Genius.com's API 

Cleaned the lyrics column by removing unnecessary words and characters/punctuations using Python's re (regular expresson) package

Created a wordcloud to see which words were prominent and frequently occuring

Words like: love, fallin and feel stood out, an indicator that the theme of the album is about falling in love

Calculated the overall sentiment score for each song using SentimentIntensityAnalyzer 

Visualized the sentiment scores for all songs from the Midnights Album using the matplotlib library in the form of a bar graph 

4 songs had highly negative scores, the highest being Anti-Hero, a song about self deprecation. 

9 songs had hihgly positive scores, which is an indicator of Taylor Swift's happiness in her romantic life. 

The code and the results can be found in the 'Midnights Sentiment Analysis -3.ipynb' notebook. 





