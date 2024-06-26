# Data Wrangle and Analyze with WeRateDogs Twitter Dataset

## Project Table of Contents:
* Gathering Data
* Assessing Data
* Cleaning Data
* Storing, Analyzing, and Visualizing Data
* Reporting

## Goal:
Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

## Introduction to the Dataset:
The dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

## Datasets:
1. **twitter_archive_enhanced.csv**: Download manually.

2. **image_predictions.tsv**:
   The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the Requests library and the following URL:
   [image_predictions.tsv](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv)

3. **tweet_json.txt**:
   Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called `tweet_json.txt`. Each tweet's JSON data should be written to its own line. Then read this `.txt` file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count. Note: Do not include your Twitter API keys, secrets, and tokens in your project submission.

## Software Required:
* pandas
* NumPy
* requests
* tweepy
* json
