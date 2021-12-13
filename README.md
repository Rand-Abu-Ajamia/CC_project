![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)


# Data Analysis: Climate Change in Light of COVID-19 Pandemic. 
By: Rand Abu Ajamia 

## Background
This year has witnessed major weather extremes confirming the reality of climate change. The IPCCC reports indicate (with high confidence) that events such as the pacific northwest heatwave, megadroughts in the west, western wildfires, hurricanes and extreme floods were influenced by climate change, and it is only the beginning to many impacts projected for the coming years in varying degrees of intensity depending on different global emission scenarios. 

Moreover, this year we extended our fight against COVID-19, the infection rate has fluctuated throughout the year with vaccination discovery and global response to the crisis. Nonetheless, the Omicron variant was first reported on 24 November 2021, shortly after the 26th UN Climate Change Conference of Parties (COP26) which was postponed last year due to the pandemic. 

This project is set out to understand -and visualise- global views of climate change in light of COVID-19 pandemic, these views are captured through social media engagement on twitter. The project seeks to find correlation between these two major global challenges that disregard country borders and human capacity to face their consequences.

**Objective**: the aim of this project to leverage twitter data to understand public views for climate change in reference to COVID-19 pandemic.

**Tools and libraries used:**
snscrape, tqdm, json, nltk, vader, numpy, pandas

## Project steps
1. Scraping Tweets
3. Identifying Sentiments using VADAR 
4. Text Pre-processing
5.1 removing "@handler"
6.2 Removing links (http | https)
7.3 Dropping duplicates
8.4 Removing Stop Words
9.5 Tokenization and lemmatization
10.6 Removing Punctuations, Numbers and Special characters
11. Feature Extraction
12. . Model Building

## Data
tbd

**Data description**
tbd

## References
1. Climate change & weather extremes: https://www.nationalgeographic.com/environment/article/this-year-extreme-weather-brought-home-reality-of-climate-change
2. Scraping tweets and analyzing Social Sentiments: https://towardsdatascience.com/selenium-tweepy-to-scrap-tweets-from-tweeter-and-analysing-sentiments-1804db3478ac
3. How to Scrape Tweets With snscrape: https://betterprogramming.pub/how-to-scrape-tweets-with-snscrape-90124ed006af
4. VADER-Sentiment-Analysis: https://github.com/cjhutto/vaderSentiment
