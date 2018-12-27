
# Data Wrangling of WeRateDogs

## Overview

This project encompasses the three phases of the data wrangling process: Gathering, Assessing and Cleaning. The dataset to be wrangled, analyzed and visualized is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs.
The whole data is gathered from different sources on different file formats, its quality and tidiness is assessed visually and programmatically, and then the data is cleaned for analysis and visualization, and finally stored.

## Install

The following packages are required to run the notebook:
•	Jupyter Notebooks
•	Python (includes json, os, re, ...)
•	pandas (includes numpy)
•	requests
•	tweepy
•	Matplotlib

Also, it is required to set up a Twitter Development account, to generate the Consumer key, Consumer_Secret, Access_Token and Access_Secret. Follow the directions in the “How to Apply” section from the link below:
https://developer.twitter.com/en/docs/basics/developer-portal/overview

## Sources

|Sources|Available on|Gathered|
|---|---|---|
|twitter-archive-enhanced.csv|‘WeRateDogs’|Twitter archive file is provided by Twitter to Udacity	Manually from Udacity’s servers|
|image_prediction.tsv|[At this link](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv)|Programatically using requests library|
|tweet_json.txt|Twitter|Programmatically scrapped from Twitter’s API using Tweepy library|


## Files

|Files|Description|
|---|---|
|wrangle_act.ipynb|Code for whole data wrangling and data analysis|
|wrangle_report.pdf|Briefly describes the wrangling work|
|act_report.pdf|It communicates the insights and displays the visualization(s) drawn from the wrangled data|
|twitter_archive_master.csv|Store the clean data|


