# Web-Scraping
Various methods of scraping websites for Data are explored here.

Workflows for scraping data from a web-page, in XML or HTML formats, are outlined.

## BeautifulSoup

### 1. [Using BeautifulSoup to parse information on URLs from an XML web-page](https://github.com/SphericalSilver/Web-Scraping/blob/master/pythonprogramming.net%20XML%20scraping.ipynb)

URLs available from the XML page were extracted, and then processed so that they could be visualized as a wordcloud:
![wordcloud](https://i.gyazo.com/bc351a17e58a56621c591dd8acbf6b67.png)

### 2. [Using BeautifulSoup to read in a table from a HTML web-page](https://github.com/SphericalSilver/Web-Scraping/blob/master/BeautifulSoup%20Diabetes%20Stats%20Web%20Scraping.ipynb)

A table with information on Diabetes occurrences in children was extracted and read into Python as a DataFrame using the BeautifulSoup library.

## Others

### 1. [Automating a Python Script to retrieve info from a web-page](https://github.com/SphericalSilver/Web-Scraping/blob/master/Web-Scraping%20Scripts.py)

A Python script is written for using the `read_html` function from the pandas library to automatically read in a table from a web-page. The script also outputs the resulting table as a csv file. 

A batch file using the script was then made, and then the script was automated using Task Scheduler to occur automatically at weekly intervals, which makes sure the table is as up to date as possible.

### 2. [Retrieving JavaScript Object Notation responses using APIs](https://github.com/SphericalSilver/Web-Scraping-API-usage/blob/master/Retrieving%20JSON%20files%20using%20APIs%2C%20ISS%20example.ipynb)

A workflow of using APIs to retrieve json format responses, and then working with them in Python to acquire information on the [ISS](https://en.wikipedia.org/wiki/International_Space_Station) was outlined here.
