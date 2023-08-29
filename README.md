# web-scraping-challenge_reja
module 11 challenge


# Background # 

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their **id** and **class** attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.


## What You're Creating ##

This new assignment consists of two technical products. Submitted the following deliverables:

- Deliverable 1: Scrape titles and preview text from Mars news articles.

- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


## Files ##

Downloaded the following files to get started:

Module 11 Challenge [files](https://bootcampspot.instructure.com/courses/3819/assignments/56638?module_item_id=999855)


## Instructions ##

**Part 1: Scrape Titles and Preview Text from Mars News**

Opened the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. I did work in this code as I followed the steps below to scrape the Mars News website.

1. Used automated browsing to visit the Mars news siteLinks to an external site. Inspected the page to identify which elements to scrape.

2. Created a Beautiful Soup object and used it to extract text elements from the website.

3. Extracted the titles and preview text of the news articles that I scraped. Stored the scraping results in Python data structures as follows:

- Stored each title-and-preview pair in a Python dictionary and, gave each dictionary two keys: title and preview. An example is the following:

      {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
     'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}

- Stored all the dictionaries in a Python list.

- Printed the list in your notebook.
