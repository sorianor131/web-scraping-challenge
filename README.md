# web-scraping-challenge
Module 11 Homework Assignment - Web Scraping Challenge

## Challenge
This challenge consists of two technical products. The following deliverables need to be submitted as part of this challenge:

1. Deliverable 1: Scrape titles and preview text from Mars news article. 
2. Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News
1. Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to extract text elements from the website.

3. Extract the titles and preview text of the news articles that were scraped. Store the results in Python data structures.

## Part 2: Scrape and Analyze Mars Weather Data
1. Use automated browsing to visit the Mars Temperature Data site. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to scrape the data in the HTML table.

3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.

4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

5. Analyze your dataset by using Pandas functions to answer the following questions:
    * How many months exist on Mars?
    * How many Martian days worth of data exist in the scraped dataset?
    * What are the coldest and the wamest months on mars?
    * Which months have the lowest and the highest atmospheric presure on Mars?
    * About how many terrestrial days exist in the Martian year?

6. Export the DataFrame to a CSV file. 

## References
* The Mars News site > https://static.bc-edx.com/data/web/mars_news/index.html
* Mars Temperature Data site > https://static.bc-edx.com/data/web/mars_facts/temperature.html