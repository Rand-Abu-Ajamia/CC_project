![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)


# Sentiment Analysis: Climate Change in Light of COVID-19 Pandemic during 2021
By: Rand Abu Ajamia 

## Background

This project is set out to understand -and visualise- global views of climate change in light of COVID-19 pandemic, these views are captured through social media engagement on twitter. The project seeks to find correlation between these two major global challenges we are currently facing.

This year has witnessed major weather extremes confirming the reality of climate change. The IPCCC reports indicate (with high confidence) that events such as the pacific northwest heatwave, megadroughts in the west, western wildfires, hurricanes and extreme floods were influenced by climate change. These weather extremes are only the beginning to many impacts projected for the coming years with varying degrees of intensity, depending on different global emission scenarios. 

Moreover, this year we have extended our fight against COVID-19. Although the infection rate has fluctuated throughout the year with vaccination discovery and global response to the crisis. Nonetheless, the Omicron variant was first reported on 24 November 2021, shortly after the rescheduled 26th UN Climate Change Conference of Parties (COP26, thus benchmarking how global crisis are interconnected and must be addressed side by side. 


**Objective**: the aim of this project to leverage twitter data to understand public views for climate change in reference to COVID-19 pandemic.

**libraries used:**
snscrape, tqdm, json, nltk, vader, numpy, pandas

## Project steps
1. Scraping Tweets using snscrape
2. Text Pre-processing
- Editing data types
- Dropping duplicates
- Dropping null values
- Removing links & Mentions (URLs & @s)
- Removing stopwords
3. Identifying sentiments using VADAR 
4. Data visualisation

## Data
The dataset was scraped from twitter twice:
- Using the search for the hashtag #climatechange, the raw data consisted of 874,413 rows i.e. tweets and 7 columns
- Using the hashtag #covid, the raw data consisted of XX rows and 7 columns

The columns in both dataset includes the following features: date, tweet ID, text, number of replies, number of retweets, number of likes and the location. 

**Data description**
Both datasets were coherent with their structure, thus the same pre-processing methods were applied. The data types didn't match the reality of the variables , some columns such as 'date' were modified accordingly. The climate change dataset included some non-english tweets which were ommited, along with nan values and few duplicates. 

**Ganttchart :** https://prod.teamgantt.com/gantt/schedule/?ids=2902801#&ids=2902801&user=&custom=&company=&hide_completed=false&date_filter=&color_filter=

## References
1. Climate change & weather extremes: https://www.nationalgeographic.com/environment/article/this-year-extreme-weather-brought-home-reality-of-climate-change
2. Scraping tweets and analyzing Social Sentiments: https://towardsdatascience.com/selenium-tweepy-to-scrap-tweets-from-tweeter-and-analysing-sentiments-1804db3478ac
3. Snscrape-twitter module: https://github.com/JustAnotherArchivist/snscrape/blob/master/snscrape/modules/twitter.py
4. VADER-Sentiment-Analysis: https://github.com/cjhutto/vaderSentiment
5. Simplifying Sentiment Analysis using VADER in Python (on Social Media Text): https://medium.com/analytics-vidhya/simplifying-social-media-sentiment-analysis-using-vader-in-python-f9e6ec6fc52f
