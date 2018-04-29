# Tweets_Analysis
This repository hosts the script of analyzing the companies support system tweet responses and topic recognition.
I am intrested in doing deep text mining studies on this data set in order to extract meaningful trends from the data. Currently there is a temporary data sample (available online) to test some simplified textual analysis, but eventually the methods will be tested on massive amounts of tweets by streaming data from Twitter using their developer API system. The current available dataset contains around 2.8 million tweets mostly tweeted between November and December 2017.


## Introduction
Many users nowadays use Twitter to complain about unsatisfactory services that they've recieved from different companies.
Based on recation time and the quality of answers from the service providers, customers would understand how much their satisfaction would matter to the service providers. Considering available text mining libraries in different programming languages, we can evaluate the efficiency of customer support services, and their success rates in satisfying customers by advising them properly!

## Word Cloud

Over 33 million words were collected categorically from all transferred tweets between customers and companies customer support services! Some times customers could've solved their issues and were thankful, however many times they weren't that much pleased with the support system responses!

![your image](/WordCloud.PNG)

## Interesting Graphs

- In Bound Tweets (Selected 5 Companies)
For the initial exploratory analysis top 5 companies with the high number of found first tweets during November and December of 2017 were identified! Some companies like Apple and Amazon had many mentioned tweets for their support team!

![your image](/tweet_counts.png)

- Sentiment Analysis
Using some simplified text processing algorithms in Python, I scored the responses of customers to the tweets wrote by customer support teams of the above mentioned companies. A positive sentiment score represents a positive message from a customer with posstive words used, however a negative sentiment score shows an unsatisfied customer with negative words used:

![your image](/Sentiment_Score.png)

It is obvious that airlines like Southwest and Delta did farely good jobs in responding to their customers issues. Even though the number of tweets asking for customer support help were higher for comapnies like Apple and Amazon, ones can easily see that those companies couldn't address their customers' issues very well! These sorts of analysis can help companies improving their performance, and developing better systems for monitoring their customers' issues.

# Project Goal

The goal for this project is to analyze massive amount of tweets from customers who asked for companies support service, and evaluate the response time and the quality of big companies' customer support services teams based on the number of positive and negative reactions from their customers.
By training the evaluation system, eventually we can utilize automation in categorizing the customers' issues, and responding to them with proper helpful suggestions.
Therefore, not only each company can have a better understaning of its own performance in satisfying customers, but also they can improve the way that they help customers to fix their issues.
