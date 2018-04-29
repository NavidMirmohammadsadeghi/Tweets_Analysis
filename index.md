# Tweets_Analysis
This repository hosts the script of analyzing the companies support system tweet responses and topic recognition
I am intrested in doing some text mining on this data set, currently it is a temporary data sample to test some methods on, eventually the methods will be tested on massive amounts of tweets.


# Introduction
Many users nowadays use Twitter to complain about poor services that they recieved from different companies.
Based on recation time and the quality of answers from the service providers, customers would understand how much their satisfaction would matter to the service provider. Considering available text mining libraries in different programming languages, we can evaluate the efficiency of customer support services, and their success rates in satisfying customers!

## Word Cloud

Over 33 million words were collected categorically from all transferred tweets between customers and companies customer support services! Some times customers could've solved their issues and were thakful, however many times they weren't that much pleased with the support system responses!

![your image](/WordCloud.PNG)
### Intresting Graphs

- In Bound Tweets (Selected 5 Companies)
For the initial exploratory analysis top 5 companies with the most number of found first tweets during November and December of 2017 were identified! Some companies like Apple had many mentioned tweets for their support team!
![](/Tweet_counts.png)
- Sentiment Analysis
Using some simplified text processing algorithms in Python, I scored the responses of customers to the tweets wrote by customer support teams of the above mentioned companies:
![](/sentiment_score.png)

# Project Goal

The goal for this project is to analyze massive amount of tweets from customers who asked for companies support service, and evaluate the response time and the quality of big companies' customer support services teams.
By training the evaluation system, eventually we can utilize automation in categorizing the customers' issues, and responding to them with proper helpful suggestions.
Therefore, not only each company can have a better understaning of its own performance in satisfying customers, but also they can improve the way that they help customers to fix their issues.
