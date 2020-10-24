# UdemyScrapyCourse-Project1-Worldometers

This is a Udemy tutorial to learn Scrapy. 
Modern Web Scraping with Python using Scrapy Splash Selenium

Link to scrapy: https://www.worldometers.info/world-population/population-by-country/

# Scrapy command:
- run scrapy script -----> scrapy crawl countries
- run scrapy shell ------> scrapy shell

- Create New Scrpay Project -------> scrapy startproject worldometers

- You can start your first spider with:
    - cd national_debt
    - scrapy genspider example example.com

- Create Scrapy spider -------> scrapy genspider countries www.worldometers.info/world-population/population-by-country


# Anaconda command: 
- install dependencies ----> conda install -c conda-forge scrapy==1.6 pylint autopep8 -y
- install iPython ---------> conda install iPython