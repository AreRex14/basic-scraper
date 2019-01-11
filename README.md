A basic python web scraper for you to gather data from the web. You can build upon this basic web scraper and make more advanced, user friendly but easy.

_Warning!_ Please make sure you comply with the permissions from [https://en.wikipedia.org/wiki/Robots_exclusion_standard](robots.txt), set the correct [https://en.wikipedia.org/wiki/User_agen](User Agent) and do not violate the Terms of Service of the sites that you want to scrape.

## Is it legal?
As long as you don't use it for harmful purpose such as spamming or business purpose(which you might need authorization to get/access the data)

- The data you will be gathering is publicly available so wouldn't be a problem, but make sure you didn't violate any copyright
- Make sure you follows the "Robots Exclusion standard" (ie honors the contents of robots.txt file)
- Set the correct user agent
- Read the website's terms of service(TOS) whether you need to acknowledge the owner and so on.
- It may also depend on the amount of data you are scraping - if you scrape to quickly it could be construed as a DoS attack, but this basic tool would not be at that level

## What is web scraping?
It is the process of extracting information and data from a website, transforming the information on a webpage into structured data for further analysis. 

## How to achieve that?
By using a web scraper. Anybody can copy the text on a webpage and paste it into another page, and web scrapers are simply the algorithms that can do it much quicker than humans.

## Install required packages

We are going to use BeautifulSoup for basic scraping.
```python
pip install BeautifulSoup4`
```
