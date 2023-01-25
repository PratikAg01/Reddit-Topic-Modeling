Reddit Topic Modeling
=====================

This project uses the `praw` library to scrape data from Reddit and the `nltk` and `lda` libraries to perform topic modeling on the data.

Getting Started
---------------

### Prerequisites

-   `praw`
-   `nltk`
-   `lda`

These libraries can be installed using pip by running `pip install praw nltk lda`

### Scraping Data

The `praw` library is used to scrape data from Reddit. The script `scraper.py` is provided to scrape data from a given subreddit. To use the script, provide your Reddit API credentials in the script, and run the script by passing the subreddit name as an argument.

### Topic Modeling

The `nltk` library is used to preprocess the data and the `lda` library is used to perform topic modeling. The script `topic_modeling.py` is provided to perform topic modeling on the data scraped from Reddit. Simply provide the location of the scraped data as an argument to the script.
