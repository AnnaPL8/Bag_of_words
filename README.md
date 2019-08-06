# word_cloud_of_emotions_text_data_analysis

Cluster analysis of textual data retrieved from Twitter

INTRODUCTION

This is an experimental project where I wanted to combine psychological measurment properties, positive and negative emotions during 
emergency situations and data analytics. 

STEPS TAKEN 

1. In order to get access to the Twitter API it was necessary to create and register the app on https://apps.twitter.com.
2. After receiving the Consumer key, Consumer secret, and Access token, around 5000 tweets for each natural disaster was retrieved.
Used Python pickle module to convert the tweets and to store them.
Used vectorizer to convert textual data 
Used Kmeans to find the clusters. 


WORD CLOUD

As a baseline I used publicly available normative/controlled data with most popular positive and negative words of emotions, 
and compared them with the words retrieved from four different queries
(the most common words used in the emergency during natural disasters such : earthquake, fire, tornado and hurricane), the total of 2000 tweets.
