# Webscraping-of-Financial-News

First step in predicting the stock prices based on news is;

### Collecting Data:
Mainly company related news which are listed nse India
  * Using twitter API 
  * Webscraping
  * Crawling
  * Kaggle
  
### Scraping Using Beautiful Soup.

BeautifulSoup library of python is meant for extracting data from html tags, using beautiful soup library we extracted data from news sources like Reuters, Moneycontrol, IIFL, Business standards and
Economic-times.

To install beautifulSoup, type this command on terminal: 
```
pip install BeautifulSoup
```

The data extracted has the following format: 
#### Date, Title, Subtitle, Content, Tags, Categories, Sources 

for Scraping code [Click here](https://github.com/Sabertoothtech/Webscraping-of-Financial-News/tree/master/ScrapingUsingBeautifulSoup).

### Using Crawler for getting data:

The data links are crawled from a website and all links in that website is saved in crawled.txt. Terminating condition of the
crawler is when **.pdf or .txt** file is received. Using the crawler we dowloaded annual reports of companies listed in nse.

for Crawler Code [Click Here](https://github.com/Sabertoothtech/Webscraping-of-Financial-News/tree/master/Crawler).

### Using Twitter API for Extracting latest news from twitter:

The twitter API is launched by twitter so that user can access the tweets worldwide and make sense out of the data.
But there are certain limitation using twitter free version i.e the access rate is slow and the number of requests are 
restricted. So, if you want good amount of data in less time and without restriction you must enroll for enterprise version 
of the api.
 

**Register for API here**: https://developer.twitter.com/content/developer-twitter/en.html

For Twitter code [Click Here](https://github.com/Sabertoothtech/Webscraping-of-Financial-News/tree/master/TwitterScraping).
