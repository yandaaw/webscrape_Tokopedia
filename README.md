# Web Scraping - Tokopedia

<p align="center">
  <img width="600" height="300" src="![iamge](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/Tokopedia.svg/1024px-Tokopedia.svg.png)">
</p>
PT Tokopedia is an electronic trading company or often called an online shop . Since its founding in 2009, Tokopedia has transformed into a unicorn that is influential not only in Indonesia but also in Southeast Asia. Until now, Tokopedia is one of the most visited marketplaces by the Indonesian people. Tokopedia also supports Micro, Small and Medium Enterprises(MSMEs) and individuals to develop their businesses by marketing their products online with the Government and other parties. One of the collaborative programs initiated by Tokopedia is the annual MAKERFEST event which has been held since March 2018. On May 17, 2021, Tokopedia and Gojek officially announced the merger and formed the GoTo Group . [6] The name GoTo itself comes from the abbreviations of Gojek and Tokopedia and also comes from the word gotong-royong.

# What is Web Scraping?
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database. Web scrapers typically take something out of a page, to make use of it for another purpose somewhere else. An example would be to find and copy names and telephone numbers, or companies and their URLs, or e-mail addresses to a list (contact scraping).

# Web Scraping Techniques
In general, there are two ways you can do this:
- Manual: a method where you copy data by copy-pasting from a website
- Automatic: a method that uses code, an application, or a browser extension.

Web scraping is now made easier with the help of browser extensions and applications. There are six commonly used web scraping techniques, namely:
1. Copying data manually
2. Using regular expressions
3. HTML parse
4. Analyze DOM
5. Using XPath
6. Using Google Sheets

# Benefits and Problems of Web Scraping
Following are the four main advantages:
1. Getting Leads
2. Comparing Massive Data
3. Optimization of Reviews, Product Pricing and Service
4. Looking for Company Information

Although web scraping is a very helpful technique in extracting site data, there are also problems to its implementation. At least, the following five things you need to remember if you want to do it:
1. No web scraping technique is 100% effective
1. The data obtained is not always neat
1. Understanding of the structure of the website page remains an obligation
1. Your access to a website may be blocked
1. Not all websites are easy to extract data

# About The Project
The main goal of this project is to gather product information from the tokopedia website, including product names, pricing, and sold products, product ratings. Seller name, seller city, and other information. The data saved in the data frame will subsequently be extracted into an excel or CSV dataset.

# Built with
- [**pandas**](https://pandas.pydata.org/)
- [**NumPy**](https://numpy.org/)
- [**pytz**](http://pytz.sourceforge.net/)
- [**Request**](https://docs.python-requests.org/en/latest/)
- [**Beautiful Soup**](https://beautiful-soup-4.readthedocs.io/en/latest/)

# Getting Started
ytz brings the Olson tz database into Python. This library allows accurate and cross platform timezone calculations using Python 2.4 or higher. It also solves the issue of ambiguous times at the end of daylight saving time, which you can read more about in the Python Library Reference (`datetime.tzinfo`). While Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work. last but not least is Requests, request allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.

Read more for [**pytz documentation**](http://pytz.sourceforge.net/), [**Beautiful Soup documentation**](https://beautiful-soup-4.readthedocs.io/en/latest/) and [**Request documentation**](https://docs.python-requests.org/en/latest/)
### **Prerequisites**
Here is how to run the library used in this project. First Install the list of libraries below on your device or kernel:
- pytz <br>
  ```
  pip install pytz
  ```
- Beautiful Soup <br>
  ```
  pip install beautifulsoup4
  ```
- Request <br>
  ```
  pip install requests
  ```
