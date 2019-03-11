---
title: "DevTweetz - Data Science Project "
layout: post
date: 1970-01-01 22:10
tag: 
image: 
projects: true
hidden: true # don't count this post in blog pagination
description: "Webapp created to compare tweets using ML"
category: project
author: 
externalLink: false
---

## DevTweetz
DevTweetz was my final project for Data Science and it was created to demonstrate mastery in the topics that were taught in class. These topics include workflow of a data scientist, machine learning libraries & algorithms (specifically pandas, scipy, tensorflow, h2o), and visualizations. 

### What is DevTweetz?
DevTweetz analyzes about 50,000 tweets between myself and 23 other Twitter users. The tweets are split into a bag of words where a term frequency analysis is performed to find my top words as well as the top words of the 23 other users. A model was trained to predict the user that I tweet the most similar to in order to detect whether this type of analysis can predict related goals, aspirations, interests, etc. Finally, for a humorous ending, a Digram Markov Chain was used on my tweets in order to predict future tweets.

### How was DevTweetz created?
A unigram, bigram and a combination of both was used in order to detect similarities in language. For extraction, Twitter's API (Tweepy) was used to pull the tweets. After extracting and cleaning the tweets, K Nearest Neighbors was performed with an optimal k of 9 to find my most similar tweeters. For the visuals, Google Visualization API was used to format and graph the data.

### Learn More
Check out the website [here](https://devtweetz.github.io/)!

---
